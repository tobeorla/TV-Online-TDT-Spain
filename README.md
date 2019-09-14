# TV-Online-TDT-Spain

[![Travis](https://img.shields.io/travis/tobeorla/TV-Online-TDT-Spain.svg)](https://travis-ci.org/tobeorla/TV-Online-TDT-Spain)

Lista de URLs de canales TDT de España - Abrir directamente con VLC u otro reproductor de vídeo.

Manual: [Cómo abrir estos canales de TDT en VLC](https://www.softzone.es/2016/12/18/ver-la-tdt-online-streaming-utilizando-tan-solo-vlc/)

Plugin Kodi: Comprime la carpeta plugin.video.tdtiberia en un fichero zip con ese mismo nombre. Sigue la guia [instalar plugin en zip](http://kodi.wiki/view/HOW-TO:Install_add-ons_from_zip_files) para instalar el plugin.

[TDTSpain2VLC] (https://github.com/EnforcerZhukov/TDTSpain2VLC) :
Script Python para descargar el listado de canales TDT por streaming de TV-Online-TDT-Spain y convertirlo a una playlist XSPF para VLC

## Modificar/Añadir nuevo canal

1. Si quieres añadir o modificar un canal, edita el fichero [tv-spain.json](https://github.com/tobeorla/TV-Online-TDT-Spain/blob/master/tv-spain.json). 
(El listado del readme junto con el estado de cada uno, se actualizarán automáticamente pasado un día)

2. Envía un PR (pull request) a este repositorio, usando la branch que se te ha creado con tus cambios: https://github.com/tobeorla/TV-Online-TDT-Spain/compare/master...tobeorla:master
- Si al menos 2 usuarios de Github responen con un `+1`, tu cambios serán añadidos automáticamente.
- Si por el contrario al menos 2 usurios responden con un `-1`, serán denegados.
- Si el administrador del respositorio está vivo, puede pasarse la votación por el forro y aplicar o denegar los cambios directamente.

## Requisitos desarrollador

Si quieres modificar el sistema revisa la disponibilidad de los streams, necesitarás:
- php
- php-curl (correspondiente a la versión de tengas de php (`php -v`), ej: php7.0-curl)

Apartir de aquí, el contenido es editado automáticamente por Travis, no añadir más contenido después de esta línea.

Status| Descripción
--- | --- |
:green_heart:|OK
:red_circle:|Link no accesible

## Status Update: **2019-09-14**

Status | Canal | URL
--- | --- | ---
:red_circle:|La 1|http://rtvev4-live.hss.adaptive.level3.net/egress/ahandler/rtvegl7/la1_lv3_aosv4_gl7/la1_lv3_aosv4_gl7.isml/la1_lv3_aosv4_gl7-audio=128000-video=1500000.m3u8
:green_heart:|La 2|http://hlsliveamdgl0-lh.akamaihd.net/i/hlslive_1@586367/master.m3u8
:red_circle:|Antena 3|https://atresplayerp-i.akamaized.net/antena3mpp/bitrate_3.m3u8
:green_heart:|Cuatro|https://livehlsdai-i.akamaihd.net/hls/live/571643/cuatro/bitrate_1.m3u8
:red_circle:|Cuatro HD|http://cuatro-mediaset-esp-live.secure.footprint.net/mediaset/cuatro/stream2/streamPlaylist.m3u8
:green_heart:|Telecinco|https://livehlsdai-i.akamaihd.net/hls/live/571640/telecinco/bitrate_1.m3u8
:red_circle:|Telecinco HD|http://telecinco-mediaset-esp-live.secure.footprint.net/mediaset/telecinco/stream2/streamPlaylist.m3u8
:red_circle:|La Sexta|https://livepull1.secure.footprint.net/lasextampp/master.m3u8
:red_circle:|A3Series|https://a3series-pull2a-a3player.secure.footprint.net/a3series/master.m3u8
:red_circle:|Nova|https://atresplayers-i.akamaized.net/geonovampp/bitrate_3.m3u8
:red_circle:|Neox|https://atresplayers-i.akamaized.net/geoneoxmpp/bitrate_3.m3u8
:red_circle:|Mega|https://atresplayers-i.akamaized.net/geomegampp/bitrate_3.m3u8
:green_heart:|Be Mad TV|https://mdslivehlsb-i.akamaihd.net/hls/live/623615/bemad/bitrate_4.m3u8
:green_heart:|Divinity|https://mdslivehls-i.akamaihd.net/hls/live/571648/divinity/bitrate_1.m3u8
:green_heart:|Real Madrid TV|http://rmtv24hweblive-lh.akamaihd.net/i/rmtv24hwebes_1@300661/master.m3u8
:green_heart:|Paramount Channel|http://paramount.live.flumotion.com/live/playlist.m3u8
:red_circle:|Disney Channel|http://cdnapi.kaltura.com/p/1068292/sp/106829200/playManifest/entryId/1_d8lnsqu0/format/applehttp/protocol/http/uiConfId/27176231/a.m3u8?referrer=aHR0cDovL2Rpc25leWNoYW5uZWwuZXM=&playSessionId=8134da47-6b06-6113-0fde-2079fb2dcca0
:red_circle:|Disney Channel|https://eslivestream-lh.akamaihd.net/i/live_1@318671/master.m3u8
:red_circle:|24h|http://hlsliveamdgl8-lh.akamaihd.net/i/hlsdvrlive_1@583030/master.m3u8
:red_circle:|Teledeporte|http://hlsliveamdgl1-lh.akamaihd.net/i/hlsdvrlive_1@39732/master.m3u8
:red_circle:|Teledeporte HD|http://hlsliveamdgl1-lh.akamaihd.net/i/hlslive_1@39598/master.m3u8
:red_circle:|TVE 60 aniversario|http://rtve-live.hds.adaptive.level3.net/hls-live/rtvegl0-irtve24lv3aomgl0/_definst_/live.m3u8
:green_heart:|13TV|http://streaming.enetres.net/091DB7AFBD77442B9BA2F141DCC182F5021/mobile/playlist.m3u8
:red_circle:|DMax|http://zba2-2-hls5-live.zahs.tv/ES_veo/master.m3u8?z32=OVZWK4S7NFSD2MJRGYZTCNJZHETG22LOOJQXIZJ5GATG2YLYOJQXIZJ5GE2TAMBGONUWOPJUMM4DAYRTGRQTSYJZGA4TEOLDMMYWMNRRGU4TEYTCGQ4TGNTEG4TGG43JMQ6TCNBZG5CTKNKFGBBUGRRTGQZTQLJTHE3TQRBYHA4UERBXIU3DQNCBEZUW42LUNFQWY4TBORST2MA
:green_heart:|FDF|https://mdslivehls-i.akamaihd.net/hls/live/571650/fdf/bitrate_1.m3u8
:red_circle:|Ten|http://cdn.sitenow.me/live/ten_azj987s/chunklist.m3u8
:red_circle:|DKiss|http://kisstvnacional.es.flash.glb.canalweb.com/kisstvnacional.es/mp4:9KISSTV.mp4/playlist.m3u8
:red_circle:|Energy|https://mdslivehls-i.akamaihd.net/hls/live/571649/energy/bitrate_1.m3u8
:red_circle:|C. Sur Andalucia - Andalucia (AN)|http://iphone-andaluciatelevision.rtva.stream.flumotion.com/rtva/andaluciatelevision-iphone-multi/main.m3u8
:red_circle:|ATV - Andalucia (AN)|http://195.55.74.205/rtva/champions-hls/stream.m3u8
:red_circle:|Aragon TV - Aragon (AR)|http://aragontv.stream.flumotion.com/aragontv/hls-live/main.m3u8
:red_circle:|TPA - Asturias (AS)|http://iphone.rtpa.stream.flumotion.com/rtpa/tv-iphone/main.m3u8
:red_circle:|IB3 - Baleares (IB)|http://ibsatiphone.ib3tv.com/iphoneliveIB3/IB3/bitrate_3.m3u8
:red_circle:|RTVC net - Canarias (CN)|http://streaming2.mad.idec.net/rtvcnet/rtvcnet.drb.smil/Playlist.m3u8
:red_circle:|Popular TV - Cantabria (CB)|http://cls.todostreaming.eu/ptvcantabria/livestream/chunklist.m3u8
:red_circle:|La Regional (WEB) - C. Mancha (CM)|http://www.movipbox.com/LAREGIONAL/guia/inicio/demo_1/print_html5_moviles.php
:red_circle:|CMM - C. Mancha (CM)|http://live-hls.rtvcm.stream.flumotion.com/rtvcm/hls-multi/main.m3u8
:red_circle:|CYL TV - C. Leon (CL)|http://nws.nice264.com/ilive/cyl/cyl_cyltvlivem_MB_348/playlist.m3u8
:green_heart:|TV3 - Cataluña (CT)|http://ccma-tva-int-abertis-live.hls.adaptive.level3.net/int/ngrp:tv3_web/playlist.m3u8
:green_heart:|324 - Cataluña (CT)|http://ccma-tva-int-abertis-live.hls.adaptive.level3.net/int/ngrp:324_web/playlist.m3u8
:green_heart:|C33 - Cataluña (CT)|http://ccma-tva-int-abertis-live.hls.adaptive.level3.net/int/ngrp:c33_web/playlist.m3u8
:green_heart:|8TV - Cataluña (CT)|http://iphone.radiocat.net:1935/livereflector/8aldia.stream/playlist.m3u8
:green_heart:|C. Extremadura - Extramadura (EX)|http://hlstv.canalextremadura.es/livetv/smil:multistream.smil/chunklist_b1596000_DVR.m3u8
:green_heart:|TVG Europa - Galicia (GA)|http://europa-crtvg.flumotion.com/playlist.m3u8
:green_heart:|TVG America - Galicia (GA)|http://america-crtvg.flumotion.com/playlist.m3u8
:red_circle:|7 RM - Murcia (MC)|http://hls0.80670-live0.dna.qbrick.com/80670-live0/murciatv/playlist.m3u8
:green_heart:|Telemadrid - Madrid (MD)|http://telemadrid-live.hls.adaptive.level3.net/hls-live/telemadrid-telemadridbis/_definst_/live.m3u8
:green_heart:|La Otra - Madrid (MD)|http://laotrahls-live.hls.adaptive.level3.net/telemadrid/laotra1/index.m3u8
:red_circle:|Libertad Digital - Madrid (MD)|http://stream-09.vty.dailymotion.com/09/dm/1/xnm032/live.isml/live.m3u8?e=1481401957&st=FfaF_FK5REWIoSlanFC8kQ
:red_circle:|Canal Parlamento - Madrid (MD)|http://congresodirectomobile.edgesuite.net/live/live6.stream/manifest.m3u8?DVR&m3u8
:green_heart:|Navarra TV - Navarra (NC)|http://nws.nice264.com/SmilLive/getLiveIOS.smil?stream=NTV_livenatvmb&system=NTV&protocol=http_cupertino/playlist.m3u8
:red_circle:|Vaughan TV - Navarra (NC)|http://vaughantv.streaming-pro.com:1935/live/vaughantv/playlist.m3u8
:green_heart:|Eitb - P.Vasco (PV)|http://etbvnogeo-lh.akamaihd.net/i/ETBEITBEUS_1@300391/master.m3u8
:red_circle:|TVR 10 - La Rioja (RI)|http://teledifusion.tv:1935/rioja/rioja/playlist.m3u8
:green_heart:|Mediterraneo TV - C.Valenciana (VC)|http://streaming.enetres.net/489DDF7FE98241D19D8970314BC9D3EF021/mobile/playlist.m3u8?idLive=021&referer=aHR0cDovL3RlbGVhbWUuY29tL3R2bWVkaXRlcnJhbmVvZW5kaXJlY3RvLw==&zz=m3u8
:green_heart:|RTV Ceuta - Ceuta (CE)|http://teledifusion.tv:1935/rtvcetv/rtvcetvlive/playlist.m3u8
:red_circle:|Ceuta TV - Ceuta (CE)|http://cls.todostreaming.eu/anguloce/livestream/chunklist.m3u8
:red_circle:|TV Melilla - Melilla (ML)|http://melillatv.hls.flumotion.com/melilla/live-hls-2/playlist.m3u8
:red_circle:|Onda Algeciras TV - Cádiz (AN)|http://cls.provideo.es/algecirastv/livestream/master.m3u8
:red_circle:|Canal Costa - Huelva (AN)|http://cls2.todostreaming.eu/azahara/IKbtqOuj/playlist.m3u8
:red_circle:|Huesca TV - Huesca (AR)|http://teledifusion.tv:1935/dia/dia/playlist.m3u8
:red_circle:|TV Ibiza-Formentera - Baleares(IB)|http://server10.streaming-pro.com:1937/live/teftvlive/playlist.m3u8
:red_circle:|Tindaya TV - Las Palmas G.C. (CN)|http://188.165.135.22/tindayatv/livestream/playlist.m3u8
:red_circle:|Popular TV - Cantabria (CB)|http://cls.todostreaming.eu/ptvcantabria/livestream/chunklist.m3u8
:red_circle:|Diocesano TV - Toledo (CM)|http://178.32.53.254/rtvd/livestream/playlist.m3u8
:red_circle:|BTV/Betevé - Barcerlona (CT)|http://api-cdn.overon.es/SmilLive/getLiveIOS/playlist.m3u8?stream=btv_stream01
:green_heart:|VOTV - Barcelona (CT)|http://video-streaming.laxarxa.com:1935/ocasional5/directe/master.m3u8
:red_circle:|Andorra TV - Lleida (CT)|http://194.158.80.31:443/live/web/master.m3u8
:red_circle:|Hit TV - Madrid (MD)|http://tst.es.flash.glb.ipercast.net/tst.es-live/live/playlist_w.m3u8
:red_circle:|Intereconomia - Madrid (MD)|http://edge3.adnstream.com:81/hls/intereconomia.m3u8
:red_circle:|Ribera TV - Valencia (VC)|http://orion.comelson.es/ribera/livestream/chunklist_w476320974.m3u8
:red_circle:|Televisió Badalona|http://cdnlive.shooowit.net/badalonatvlive/smil:live.smil/playlist.m3u8
:green_heart:|Televisió de Girona|http://ventdelnord.tv:8080/girona/directe.m3u8
:red_circle:|Tarragona TV|http://cdns724ste1010.shooowit.net/tac12live/amlst:live/playlist.m3u8
:red_circle:|El Punt Avui TV|http://cdns724ste1010.shooowit.net/puntavuitvlive/smil:live.smil/playlist.m3u8
:red_circle:|Terrassa TV|http://173.212.214.184:1935/terrassaweb/terrassaweb/playlist.m3u8
:red_circle:|Sevilla F.C.|http://sevillafc_live-lh.akamaihd.net/i/video_0@354142/index_0700_av-p.m3u8
:red_circle:|BETISTV|http://rbetis-hls.flumotion.com/rbetis/live/chunklist.m3u8
:red_circle:|Nasa TV - EEUU|http://nasatv-lh.akamaihd.net/i/NASA_101@319270/master.m3u8
:red_circle:|Cordoba Internacional|http://streaming.enetres.net/69BF7C8664934222BA3F58530449B8CE021/mobile/playlist.m3u8
:red_circle:|HispanTV|http://107.189.40.49:1935/live/hispantv/playlist.m3u8
:red_circle:|Russia Today Español|https://secure-streams.akamaized.net/rt-esp/index.m3u8
:green_heart:|À Punt - C. Valenciana (VC)|https://cflive-emea.live-delivery.ooyala.com/out/u/jb44pwd2tj7w5/111819/wyYXIxZTE6okZbyKLzxq8TXa4a-SQlAO/cs/d77d4356674b449695b1c0f19fbd6fae_6.m3u8
:red_circle:|Boing|https://mdslivehls-i.akamaihd.net/hls/live/571647/boing/bitrate_1.m3u8
:green_heart:|Fox News Talk|https://fnurtmp-f.akamaihd.net/i/FNRADIO_1@92141/master.m3u8
:green_heart:|ABC News Live|https://abclive1-lh.akamaihd.net/i/abc_live10@420897/master.m3u8
