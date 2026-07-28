---
title: HttpWebClientProtocol
second_title: Aspose.Slides C++ API hivatkozás
description: "Ez az alaposztály minden HTTP-t használó XML Web szolgáltatás kliens proxy-ban használatos. Az osztály példányait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból stack-en vagy az operator new használatával, mert ez futásidejű hibákhoz és/vagy assert hibákhoz vezet. Mindig csomagolja be az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja a függvények argumentumaként."
type: docs
weight: 14
url: /hu/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol osztály


This base class is used in all XML [Web](../../system.web/) service client proxies that use HTTP. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Megszakítja a kérést. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | A megadott kérésből származó sütiket hozzáadja a belső süti tárolóhoz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Reference type objects are compared in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Value type objects are compared in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | Visszaad egy értéket, amely jelzi, hogy a kliens követi-e a szerver átirányításait. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | Visszaadja a kliens tanúsítványainak gyűjteményét. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Visszaadja a kapcsolatcsoport nevét. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | Visszaad egy tárolót, amely a sütik tárolására szolgál. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Visszaadja a hitelesítési információt. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | Visszaad egy értéket, amely jelzi, hogy a kitömörítés engedélyezett-e. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Visszaad egy értéket, amely jelzi, hogy az előhitelesítés engedélyezett-e. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | Visszaadja a proxy információkat. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Visszaadja a kódolást, amely a kliens kéréseinek elkészítéséhez használatos. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Visszaadja a várakozási időt, amelyet a kérés időtúllépése előtt kell várni. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | Visszaad egy értéket, amely jelzi, hogy a kapcsolatmegosztás engedélyezett-e, amikor a kliens NTLM hitelesítést használ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Visszaadja az XML [Web](../../system.web/) szolgáltatás URI-ját. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Visszaadja az XML [Web](../../system.web/) szolgáltatás URL-jét. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Visszaad egy értéket, amely jelzi, hogy a 'Credential' tulajdonság egyenlő-e a 'DefaultCredentials' tulajdonsággal. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | Visszaad egy értéket a 'User-Agent' fejlécből. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-al. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a kliens követi-e a szerver átirányításait. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Beállítja a kapcsolatcsoport nevét. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Beállít egy tárolót, amely a sütik tárolására szolgál. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Beállítja a hitelesítési információt. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a kitömörítés engedélyezett-e. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Beállít egy értéket, amely jelzi, hogy az előhitelesítés engedélyezett-e. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Beállítja a proxy információkat. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Beállítja a kódolást, amely a kliens kéréseinek elkészítéséhez használatos. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Beállítja a várakozási időt, amelyet a kérés időtúllépése előtt kell várni. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a kapcsolatmegosztás engedélyezett-e, amikor a kliens NTLM hitelesítést használ. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Beállítja az XML [Web](../../system.web/) szolgáltatás URI-ját. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Beállítja az XML [Web](../../system.web/) szolgáltatás URL-jét. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a 'Credential' tulajdonság egyenlő-e a 'DefaultCredentials' tulajdonsággal. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | Beállít egy értéket a 'User-Agent' fejlécben. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett) állítja be. Lehetővé teszi a mutatók váltását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti, majd visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok sztringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [WebClientProtocol](../webclientprotocol/)
* Névtere [System::Web::Services::Protocols](../)
* Könyvtár [Aspose.Slides](../../)