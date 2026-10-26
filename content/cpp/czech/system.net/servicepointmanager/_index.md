---
title: ServicePointManager
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Spravuje fáze životního cyklu (vytváření, údržbu a mazání) instancí třídy ServicePoint. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 430
url: /cs/system.net/servicepointmanager/
---
## ServicePointManager třída

Spravuje fáze životního cyklu (vytváření, údržbu a mazání) instancí [ServicePoint](../servicepoint/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument.

```cpp
class ServicePointManager : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Získává politiku certifikátu. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Získává hodnotu, která určuje, zda musí být certifikát kontrolován proti seznamu odvolaných certifikátů certifikační autority. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Získává maximální počet souběžných připojení, který je povolen instancemi třídy ServicePoint. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Získává časový limit v milisekundách, během kterého je DNS rozlišení považováno za platné. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Získává hodnotu, která určuje, zda DNS rozlišení rotuje mezi použitelnými IP adresami. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Vrací šifrovací politiku, která je použita aktuální instancí. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Získává hodnotu, která určuje, zda instance třídy ServicePoint používají chování 100-Continue. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Získává maximální dobu nečinnosti instancí třídy ServicePoint. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Získává maximální počet instancí třídy ServicePoint, které může spravovat aktuální instance. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Získává hodnotu, která určuje, zda výstupní sokety připojení používají možnost 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Získává typ bezpečnostního protokolu používaný instancemi třídy ServicePoint, které jsou spravovány aktuální instancí. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Získává zpětné volání, které se používá k ověření certifikátu serveru. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Získává hodnotu, která určuje, zda instance třídy ServicePoint používají Nagle algoritmus. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Nastavuje politiku certifikátu. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Nastavuje hodnotu, která určuje, zda musí být certifikát kontrolován proti seznamu odvolaných certifikátů certifikační autority. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Nastavuje maximální počet souběžných připojení, který je povolen instancemi třídy ServicePoint. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Nastavuje časový limit v milisekundách, během kterého je DNS rozlišení považováno za platné. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Nastavuje hodnotu, která určuje, zda DNS rozlišení rotuje mezi použitelnými IP adresami. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Nastavuje hodnotu, která určuje, zda instance třídy ServicePoint používají chování 100-Continue. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Nastavuje maximální dobu nečinnosti instancí třídy ServicePoint. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Nastavuje maximální počet instancí třídy ServicePoint, které může spravovat aktuální instance. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Nastavuje hodnotu, která určuje, zda výstupní sokety připojení používají možnost 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Nastavuje typ bezpečnostního protokolu používaný instancemi třídy ServicePoint, které jsou spravovány aktuální instancí. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Nastavuje zpětné volání, které se používá k ověření certifikátu serveru. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Nastavuje hodnotu, která určuje, zda instance třídy ServicePoint používají Nagle algoritmus. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Nastavuje hodnotu, která určuje, zda je možnost 'Keep-Alive' povolena. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Výchozí počet neperzistentních spojení. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Výchozí počet perzistentních spojení. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)