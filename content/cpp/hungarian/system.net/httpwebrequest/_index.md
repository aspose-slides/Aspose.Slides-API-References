---
title: HttpWebRequest
second_title: Aspose.Slides C++ API referencia
description: "A HTTP webkérést képviseli. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja a függvények argumentumaként való átadásához."
type: docs
weight: 274
url: /hu/system.net/httpwebrequest/
---
## HttpWebRequest osztály

Az HTTP webkérést képviseli. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvényeknek argumentumként való átadásához.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [Abort](./abort/)() override | Megszakítja a jelenlegi kérés. |
| virtual void [AddRange](./addrange/)(**int32_t**) | Hozzáadja a '[Range](../../system/range/)' fejlécet az aktuális kéréshez. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | Hozzáadja a '[Range](../../system/range/)' fejlécet az aktuális kéréshez. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Aszinkron műveletet indít, amely adat írásához streamet szerez a erőforráshoz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Aszinkron kérést indít a erőforráshoz. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | Új példányt hoz létre a [WebRequest](../webrequest/) osztályból a megadott URI-val. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Új példányt hoz létre a [WebRequest](../webrequest/) osztályból a megadott URI-val. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Létrehoz egy [WebRequest](../webrequest/) leszármaztatott objektumot a megadott URI-sémához. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | Új példányt hoz létre a [WebRequest](../webrequest/) osztályból a megadott URI-val. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Új példányt hoz létre a [WebRequest](../webrequest/) osztályból a megadott URI-val. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Megvárja, amíg a megadott aszinkron stream-lekapcsolási művelet befejeződik. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Megvárja, amíg a megadott aszinkron erőforrás-kérés befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia-típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték-típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | Visszaadja az 'Accept' HTTP fejléc értékét. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Visszaad egy értéket, amely jelzi, hogy a kérés kövesse-e az átirányításokat. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | Visszaad egy értéket, amely jelzi, hogy a erőforrásból érkező adatot pufferelni kell-e. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | Visszaad egy értéket, amely jelzi, hogy a küldéshez a pufferelés engedélyezett-e. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | Visszaadja a gyorsítótár-szabályt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Visszaadja az aktuális kéréshez kapcsolódó tanúsítványok gyűjteményét. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | Visszaadja a kapcsolatcsoport nevét. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | Visszaadja a küldendő kérésadat bájtok számát. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Visszaadja a kérés MIME-típusát. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | Visszaad egy időkorlátot, amíg a 100-Continue állapotkód megérkezik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Visszaad egy süti-tárolót, amely az aktuális webkéréssel kapcsolódik. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | Visszaadja a jelenlegi kéréshez tartozó hitelesítési információt. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | Visszaadja a globális HTTP proxy-t. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | Visszaad egy értéket, amely jelzi, hogy érkezett-e válasz. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | Visszaadja a HTTP fejlécek gyűjteményét. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | Visszaad egy értéket, amely jelzi, hogy a jelenlegi kérésnek tartalmaznia kell a 'Keep-Alive' fejlécet. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | Visszaad egy maximális engedélyezett átirányítások számát. |
| [String](../../system/string/) [get_Method](./get_method/)() override | Visszaadja a HTTP metódust. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | Visszaad egy értéket, amely jelzi, hogy a kérésnek pre-authentikáltnak kell lennie. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | Visszaadja az előtaglista. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | Visszaadja a HTTP proxy-t. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | Visszaadja a 'Referer' fejléc értékét. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | Visszaadja a kérés URI-ját. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | Visszaad egy értéket, amely jelzi, hogy az adatot szegmensekben kell küldeni. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | Visszaad egy szolgáltatási pontot, amely a hálózati kapcsolatot képviseli az erőforráshoz. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | Visszaad egy értéket, amely jelzi, hogy a jelenlegi kérés használhat-e süti-tárolót. |
| **int32_t** [get_Timeout](./get_timeout/)() override | Visszaad egy időt miliszekundumban, amely után a kérés időtúllép. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | Visszaad egy értéket, amely jelzi, hogy a 'Credential' tulajdonság egyenlő-e a 'DefaultCredentials' tulajdonsággal. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | Visszaadja a 'User-Agent' fejléc értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | Visszaadja a streamet az adat írásához a erőforráshoz. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | Visszaadja a jelenlegi webkéréssel kapcsolódó web-választ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Új példányt hoz létre. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi alosztályok másolás-konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi alosztályok másolás-konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az érték-típusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | Regisztrálja a [WebRequest](../webrequest/) leszármaztatottat a megadott URI-hoz. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | Beállítja az 'Accept' HTTP fejléc értékét. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a kérés kövesse-e az átirányításokat. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a erőforrásból érkező adatot pufferelni kell-e. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a küldéshez a pufferelés engedélyezett-e. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | Beállítja a gyorsítótár-szabályt. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | Beállítja a jelenlegi kéréshez kapcsolódó tanúsítványok gyűjteményét. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | Beállítja a kapcsolatcsoport nevét. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | Beállítja a küldendő kérésadat bájtok számát. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | Beállítja a kérés MIME-típusát. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | Beállít egy időkorlátot, amíg a 100-Continue állapotkód megérkezik. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | Beállít egy süti-tárolót, amely az aktuális webkéréssel kapcsolódik. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | Beállítja a jelenlegi kéréshez tartozó hitelesítési információt. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | Beállítja a globális HTTP proxy-t. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | Beállítja a HTTP fejlécek gyűjteményét. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a jelenlegi kérésnek tartalmaznia kell a 'Keep-Alive' fejlécet. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | Beállít egy maximális engedélyezett átirányítások számát. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | Beállítja a HTTP metódust. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | Beállít egy értéket, amely jelzi, hogy a kérésnek pre-authentikáltnak kell lennie. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | Beállítja az előtaglistát. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | Beállítja a HTTP verziót. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | Beállítja a HTTP proxy-t. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | Beállítja a 'Referer' fejléc értékét. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | Beállít egy értéket, amely jelzi, hogy az adatot szegmensekben kell küldeni. |
| void [set_Timeout](./set_timeout/)(int) override | Beállít egy időt miliszekundumban, amely után a kérés időtúllép. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | Beállít egy időt miliszekundumban, amely után a kérés időtúllép. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | Beállít egy értéket, amely jelzi, hogy a 'Credential' tulajdonság egyenlő-e a 'DefaultCredentials' tulajdonsággal. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | Beállítja a 'User-Agent' fejléc értékét. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a shared helyett) állítja be. Lehetővé teszi, hogy a tárolók mutatóit gyengére módra állítsa át. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [WebRequest](../webrequest/)
* Névtér [System::Net](../)
* Könyvtár [Aspose.Slides](../../)