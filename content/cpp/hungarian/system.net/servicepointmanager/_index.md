---
title: ServicePointManager
second_title: Aspose.Slides C++ API referencia
description: "Kezeli a ServicePoint osztálypéldányok életciklus-szakaszait (létrehozás, karbantartás és törlés). Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozz létre példányt ebből a típusból a veremben vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagold be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használd argumentumként a függvényeknek való átadáskor."
type: docs
weight: 430
url: /hu/system.net/servicepointmanager/
---
## ServicePointManager osztály


a [ServicePoint](../servicepoint/) osztály példányainak életciklus-szakaszait (létrehozás, karbantartás és törlés) kezeli. Az ilyen osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ServicePointManager : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Lekéri egy tanúsítványpolitikát. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Lekéri azt az értéket, amely jelzi, hogy a tanúsítványt ellenőrizni kell-e a hitelesítésszolgáltató visszavonási listája alapján. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Lekéri a ServicePoint-osztály példányai által megengedett egyidejű kapcsolatok maximális számát. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Lekéri a DNS-feloldás érvényességét meghatározó időtartamot ezredmásodpercben. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Lekéri azt az értéket, amely jelzi, hogy a DNS-feloldás körbejár-e a megfelelő IP-címek között. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Visszaadja a jelenlegi példány által használt titkosítási szabályt. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Lekéri azt az értéket, amely jelzi, hogy a ServicePoint-osztály példányai a 100-Continue viselkedést használják-e. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Lekéri a ServicePoint-osztály példányainak maximális üresjárati időt. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Lekéri a ServicePoint-osztály példányainak maximális számát, amelyet a jelenlegi példány kezelni tud. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Lekéri azt az értéket, amely jelzi, hogy a kimenő kapcsolat-socketek a 'SO_REUSE_UNICASTPORT' opciót használják-e. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Lekéri a jelenlegi példány által kezelt ServicePoint-osztály példányok által használt biztonsági protokoll típust. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Lekéri a szerver tanúsítványának ellenőrzésére használt visszahívási függvényt. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Lekéri azt az értéket, amely jelzi, hogy a ServicePoint-osztály példányai a Nagle-algoritmust használják-e. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusról. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Beállít egy tanúsítványpolitikát. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Beállítja azt az értéket, amely jelzi, hogy a tanúsítványt ellenőrizni kell-e a hitelesítésszolgáltató visszavonási listája alapján. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Beállítja a ServicePoint-osztály példányai által megengedett egyidejű kapcsolatok maximális számát. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Beállítja a DNS-feloldás érvényességének időtartamát ezredmásodpercben. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Beállítja azt az értéket, amely jelzi, hogy a DNS-feloldás körbejár-e a megfelelő IP-címek között. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Beállítja azt az értéket, amely jelzi, hogy a ServicePoint-osztály példányai a 100-Continue viselkedést használják-e. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Beállítja a ServicePoint-osztály példányainak maximális üresjárati időt. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Beállítja a ServicePoint-osztály példányainak maximális számát, amelyet a jelenlegi példány kezelhet. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Beállítja azt az értéket, amely jelzi, hogy a kimenő kapcsolat-socketek a 'SO_REUSE_UNICASTPORT' opciót használják-e. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Beállítja a jelenlegi példány által kezelt ServicePoint-osztály példányok által használt biztonsági protokoll típust. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Beállítja a szerver tanúsítványának ellenőrzésére használt visszahívási függvényt. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Beállítja azt az értéket, amely jelzi, hogy a ServicePoint-osztály példányai a Nagle-algoritmust használják-e. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Beállítja azt az értéket, amely jelzi, hogy a 'Keep-Alive' opció engedélyezve van-e. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóvá (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerekben való gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Az alapértelmezett nem tartós kapcsolatok száma. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Az alapértelmezett tartós kapcsolatok száma. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Net](../)
* Könyvtár [Aspose.Slides](../../)