JOSN请求和返回示例
===================

banner请求示例
--------------

.. sourcecode:: js

		{
		    "id": "0bum3G1CQfE440EQrP0tUPoy3MGFhC",
		    "imp": [
		        {
		            "id": "1",
		            "banner": {
		                "w": 640,
		                "h": 100,
		                "pos": 0
		            },
		            "ins
		tl": false,
		            "tagid": "zapf49b17bbd2a551e478a485a3a82e052fd6f5652c",
		            "bidfloor": 130,
		            "bidfloorcur": "CNY",
		            "ext": {
		                "inventory_type
		s": [
		                    1,
		                    2,
		                    4,
		                    5
		                ]
		            }
		        }
		    ],
		    "app": {
		        "id": "1000481",
		        "name": "国内-安卓-消灭星星官方正版",
		        "ver": "4.5.1",
		        "bundle": "com.brianbaek.popstar"
		    },
		    "device": {
		        "dnt": false,
		        "ua": "Dalvik/2.1.0(Linux;U;Android5.1.1;vivoY31ABuild/LMY47V)",
		        "ip": "223.104.171.147",
		        "geo": {
		            "lat": 27.970472,
		            "lon": 116.34153,
		            "country": "CHN",
		            "region": "北京",
		            "city": "北京",
		            "type": 2,
		            "ext": {
		                "accu": 0
		            }
		        },
		        "didsha1": "5d3b81d9b4
		fc532586410026835dc35f93697695",
		        "dpidsha1": "558d608a909c114d03536b28300e48d98dcd0abb",
		        "make": "vivo",
		        "model": "vivoY31A",
		        "o
		s": "android",
		        "osv": "5.1.1",
		        "w": 540,
		        "h": 960,
		        "ppi": 240,
		        "connectiontype": 6,
		        "devicetype": 4,
		        "macsha1": "4c647a8d9efd629cd238c9c
		0dc3c7928b1aa8671",
		        "ext": {
		            "plmn": "46002",
		            "imei": "862262030529799",
		            "imsi": "460029329554417",
		            "mac": "9c:a5:c0:cb:0a:e7",
		            "and
		roid_id": "b130955d7ef56ed4",
		            "adid": "",
		            "orientation": 1
		        }
		    },
		    "ext": {
		        "version": 1,
		        "need_https": false
		    }
		}

banner返回示例
---------------

.. sourcecode:: js

		{
		    "id": "0bts0K1CQgtF0zJA6R1ZzppG4CJ3b4",
		    "seatbid": [
		        {
		            "bid": [
		                {
		                    "id": "27170321175320259213",
		                    "impid": "27170321175320259213",
		                    "price": 0.1,
		                    "adid": "ac990ea25bca7474c2553679e3dd33c6",
		                    "w": 640,
		                    "h": 100,
		                    "iurl": "http://img.pxene.com/dav/65d106ff-2cb9-4ae7-a2d8-897fe3f05f64/image/37f5e37fb84945bcb4f29bdb6dbce990.jpg",
		                    "adm": "",
		                    "ext": {
		                        "clkurl": "http://e.cn.miaozhen.com/r/k=2038947&p=75Y7B&dx=__IPDX__&rt=2&ns=183.16.2.121&ni=__IESID__&v=__LOC__&xa=__ADPLATFORM__&ro=sm&mo=0&m0=__OPENUDID__&m0a=__DUID__&m1=__ANDROIDID1__&m1a=6e20e140cfd73735006479b824d9a1fd&m2=b2196f839dae8187e6b2c1931ca847f6&m4=__AAID__&m5=__IDFA__&m6=__MAC1__&m6a=__MAC__&o=http://site.pxene.com/minisiteWap/Accord_3h/",
		                        "imptrackers": [
		                            "http://sapi.wanzhuanmobile.com/phone/notify.php?act=show&log=dspid%3D101%26uniplayid%3D1636400010%26rid%3D27170321175320259213%26adid%3DSDK201616090411451r7ykol3qo7e0ou%26wzid%3D1010009%26pkg%3Dcom.zplay.migupopstar.mi%26did%3D5c8ade2b7a036131f7c7d25aeb08e2cc%26opt%3D46000%26plt%3D1%26slotid%3Dbanner%26ads%3D640x100%26sdkv%3D6%26ts%3D1490090000%26ip%3D183.16.2.121",
		                            "http://open.adview.cn/agent/openDisplay.do?st=0&uuidEncType=0&sv=0&src=75&sy=0&nt=&adi=20170321-175320_5366_130-1030-dKts-608_1&bi=com.brianbaek.popstar&ai=lP9I8FoBAABwFVtCG1dCYDcl1u5-bTTsiRPP7JLObCfdc7rllsjtV0RYEQ4uwqRrFFz2qqWIEfdeBdEdZN2nL0YNdmYYV4nGsTrpJSnPCNcEPPxcS4c-PGWdYv2p5NeOUxdkoG2xwJSZOpJrLaVP-p5VACHF1peyAcXmszjpDq6ic7jmKop9f_bpKb0mq1EY3aLJiBEQSBL1VT82qQpkaKboKeo5QKM1llQEKDBYtsvF-tnogFjY-anhbTqHg10&ud=864595026401350&andt=0&as=640x100&se=46000&cv=&rqt=1&ti=1490090005&tm=0&to=dbdb4790f0cc46f1fdd6facee9bc1845&aid=SDK201616090411451r7ykol3qo7e0ou&ro=1&ca=0",
		                            "http://ip2.pxene.com/ic?adx=14&bid=20170321-175320_bidreq_130-1030-NGzw-591&mtype=m&mapid=d2495550-d1a0-4fde-81d4-fdc634451a36&deviceid=c1019e7dbcdee277d3ec15be7cccfb554f737c5b&deviceidtype=97&appid=e1aa0807c3d23e49311b73a3580dd77a&nw=1&os=2&tp=1&reqip=183.16.2.121&gp=1156440300&mb=3&op=1&md=MI+3",
		                            "http://g.cn.miaozhen.com/x/k=2038947&p=75Y7B&dx=__IPDX__&rt=2&ns=183.16.2.121&ni=__IESID__&v=__LOC__&xa=__ADPLATFORM__&mo=0&m0=__OPENUDID__&m0a=__DUID__&m1=__ANDROIDID1__&m1a=6e20e140cfd73735006479b824d9a1fd&m2=b2196f839dae8187e6b2c1931ca847f6&m4=__AAID__&m5=__IDFA__&m6=__MAC1__&m6a=__MAC__&o="
		                        ],
		                        "clktrackers": [
		                            "http://api.wanzhuanmobile.com/phone/notify.php?act=click&log=dspid%3D101%26uniplayid%3D1636400010%26rid%3D27170321175320259213%26adid%3DSDK201616090411451r7ykol3qo7e0ou%26wzid%3D1010009%26pkg%3Dcom.zplay.migupopstar.mi%26did%3D5c8ade2b7a036131f7c7d25aeb08e2cc%26opt%3D46000%26plt%3D1%26slotid%3Dbanner%26ads%3D640x100%26sdkv%3D6%26ts%3D1490090000%26ip%3D183.16.2.121",
		                            "http://open.adview.cn/agent/openClick.do?st=0&uuidEncType=0&sv=0&src=75&sy=0&nt=&adi=20170321-175320_5366_130-1030-dKts-608_1&bi=com.brianbaek.popstar&ai=lP9I8FoBAABwFVtCG1dCYDcl1u5-bTTsiRPP7JLObCfdc7rllsjtV0RYEQ4uwqRrFFz2qqWIEfdeBdEdZN2nL0YNdmYYV4nGsTrpJSnPCNcEPPxcS4c-PGWdYv2p5NeOUxdkoG2xwJSZOpJrLaVP-p5VACHF1peyAcXmszjpDq6ic7jmKop9f_bpKb0mq1EY3aLJiBEQSBL1VT82qQpkaKboKeo5QKM1llQEKDBYtsvF-tnogFjY-anhbTqHg10&ud=864595026401350&andt=0&as=640x100&se=46000&cv=&rqt=1&ti=1490090005&tm=0&to=dbdb4790f0cc46f1fdd6facee9bc1845&aid=SDK201616090411451r7ykol3qo7e0ou&ro=1&ca=0",
		                            "http://cl2.pxene.com/ic?adx=14&bid=20170321-175320_bidreq_130-1030-NGzw-591&mtype=c&mapid=d2495550-d1a0-4fde-81d4-fdc634451a36&deviceid=c1019e7dbcdee277d3ec15be7cccfb554f737c5b&deviceidtype=97&appid=e1aa0807c3d23e49311b73a3580dd77a&nw=1&os=2&tp=1&reqip=183.16.2.121&gp=1156440300&mb=3&op=1&md=MI+3&url="
		                        ],
		                        "title": "",
		                        "desc": "",
		                        "action": 1,
		                        "html_snippet": "",
		                        "inventory_type": 1
		                    }
		                }
		            ]
		        }
		    ]
		}


插屏请求示例
--------------

.. sourcecode:: js

		{
		    "id": "0bum1K1CQfE62Ae9r23W91zl4bip18",
		    "imp": [
		        {
		            "id": "1",
		            "banner": {
		                "w": 720,
		                "h": 1080,
		                "pos": 0
		            },
		            "instl": true,
		            "tagid": "zapf7e40c242176f01fd5db1af86146a6de00dde23b",
		            "bidfloor": 800,
		            "bidfloorcur": "CNY",
		            "ext": {
		                "is_splash_screen": true,
		                "inventory_types": [
		                    1
		                ]
		            }
		        }
		    ],
		    "app": {
		        "id": "1007875",
		        "name": "QueryViolations",
		        "ver": "",
		        "bundle": "cn.eclicks.wzsearch"
		    },
		    "device": {
		        "dnt": false,
		        "ua": "Mozilla/5.0(Linux;Android6.0.1;OPPOR9sBuild/MMB29M;wv)AppleWebKit/537.36(KHTML,likeGecko)Version/4.0Chrome/46.0.2490.76MobileSafari/537.36",
		        "ip": "117.173.83.146",
		        "geo": {
		            "lat": 31.359089,
		            "lon": 103.49656,
		            "country": "CHN",
		            "region": "四川",
		            "city": "成都",
		            "type": 2,
		            "ext": {
		                "accu": 0
		            }
		        },
		        "didsha1": "88206dfa4841569b3b61f27a3775d030cd6104c2",
		        "dpidsha1": "1592348a810c27d651b5ef8290e50e7514da2502",
		        "make": "",
		        "model": "OPPOR9s",
		        "os": "android",
		        "osv": "6.0.1",
		        "w": 1080,
		        "h": 1920,
		        "ppi": 480,
		        "connectiontype": 2,
		        "devicetype": 4,
		        "macsha1": "c1976429369bfe063ed8b3409db7c7e7d87196d9",
		        "ext": {
		            "plmn": "46001",
		            "imei": "864083031808612",
		            "imsi": "",
		            "mac": "02:00:00:00:00:00",
		            "android_id": "705cce10d9d051a8",
		            "adid": "",
		            "orientation": 1
		        }
		    },
		    "ext": {
		        "version": 1,
		        "need_https": false
		    }
		}

插屏返回示例
---------------

.. sourcecode:: js

		{
		    "id": "0bsZ061CQfE403tMax38YlB71cvWlH",
		    "seatbid": [
		        {
		            "bid": [
		                {
		                    "id": "3e56c4f0b81b470196f671c96e1be5d9",
		                    "impid": "1",
		                    "price": 1100,
		                    "adid": "370",
		                    "nurl": "http://dsptrack.ad-mex.com/winnotice?requestid=0bsZ061CQfE403tMax38YlB71cvWlH&adgroupid=86&netid=018&netname=adszp&devicetype=HIGHEND_PHONE&os=android&connectiontype=CELL_4G&material_id=370&adid=NA&android_id=bbd424977f85c210&android_id_md5=NA&android_id_sha1=4e5065c08b0e5fcbdf49f298753d39ae98ebd9f2&imei=869896027210369&imei_md5=NA&imei_sha1=beb7991f15e3dac8dba6e9e03c0c41557f929c06&deviceID=869896027210369&mac=c4%3A66%3A99%3A9c%3A63%3Af8&mac_md5=NA&mac_sha1=5edfc6b4ece376ecaeb7cb1e96371e28925bfd31&remote_addr=223.104.108.146&cur_adv=RMB&cur_adx=RMB&adver_id=6&campaign_id=18&resptimestamp=20170321170000664&height=960&width=640&make=NA&model=vivoX6A&bundle=com.vlife&ip=223.104.108.146&app_name=VLife&material_type=banner",
		                    "adomain": [
		                        "http://www.adidas.com.cn/"
		                    ],
		                    "bundle": "",
		                    "iurl": "http://res.ad-mex.com/dspres/upload/20170307/88b58192-c86a-43dc-a4c2-69a5bd84f820.jpg",
		                    "cid": "18",
		                    "crid": "370",
		                    "w": 640,
		                    "h": 960,
		                    "ext": {
		                        "imptrackers": [
		                            "http://g.cn.miaozhen.com/x/k=2039081&p=75VMG&dx=__IPDX__&rt=2&ns=223.104.108.146&ni=__IESID__&v=__LOC__&xa=__ADPLATFORM__&mo=0&m0=__OPENUDID__&m0a=__DUID__&m1=bbd424977f85c210&m1a=__ANDROIDID__&m2=0f11e9b670e033f52da2e3a910523cf0&m4=__AAID__&m5=__IDFA__&m6=__MAC1__&m6a=__MAC__&o=",
		                            "http://dsptrack.ad-mex.com/adImp?requestid=0bsZ061CQfE403tMax38YlB71cvWlH&adgroupid=86&netid=018&netname=adszp&devicetype=HIGHEND_PHONE&os=android&connectiontype=CELL_4G&material_id=370&adid=NA&android_id=bbd424977f85c210&android_id_md5=NA&android_id_sha1=4e5065c08b0e5fcbdf49f298753d39ae98ebd9f2&imei=869896027210369&imei_md5=NA&imei_sha1=beb7991f15e3dac8dba6e9e03c0c41557f929c06&deviceID=869896027210369&mac=c4%3A66%3A99%3A9c%3A63%3Af8&mac_md5=NA&mac_sha1=5edfc6b4ece376ecaeb7cb1e96371e28925bfd31&remote_addr=223.104.108.146&cur_adv=RMB&cur_adx=RMB&adver_id=6&campaign_id=18&resptimestamp=20170321170000664&height=960&width=640&make=NA&model=vivoX6A&bundle=com.vlife&ip=223.104.108.146&app_name=VLife&material_type=banner&price={AUCTION_BID_PRICE}"
		                        ],
		                        "clktrackers": [
		                            "http://e.cn.miaozhen.com/r/k=2039081&p=75VMG&dx=__IPDX__&rt=2&ns=__IP__&ni=__IESID__&v=__LOC__&xa=__ADPLATFORM__&vo=32d0b8d2a&vr=2&o=http%3A%2F%2Fad.yoho.cn%2Fhtml5%2F2017%2F02%2Fadidas%2Findex.html",
		                            "http://dsptrack.ad-mex.com/adClick?requestid=0bsZ061CQfE403tMax38YlB71cvWlH&adgroupid=86&netid=018&netname=adszp&devicetype=HIGHEND_PHONE&os=android&connectiontype=CELL_4G&material_id=370&adid=NA&android_id=bbd424977f85c210&android_id_md5=NA&android_id_sha1=4e5065c08b0e5fcbdf49f298753d39ae98ebd9f2&imei=869896027210369&imei_md5=NA&imei_sha1=beb7991f15e3dac8dba6e9e03c0c41557f929c06&deviceID=869896027210369&mac=c4%3A66%3A99%3A9c%3A63%3Af8&mac_md5=NA&mac_sha1=5edfc6b4ece376ecaeb7cb1e96371e28925bfd31&remote_addr=223.104.108.146&cur_adv=RMB&cur_adx=RMB&adver_id=6&campaign_id=18&resptimestamp=20170321170000664&height=960&width=640&make=NA&model=vivoX6A&bundle=com.vlife&ip=223.104.108.146&app_name=VLife&material_type=banner"
		                        ],
		                        "clkurl": "http://ad.yoho.cn/html5/2017/02/adidas/index.html"
		                    }
		                }
		            ]
		        }
		    ]
		}