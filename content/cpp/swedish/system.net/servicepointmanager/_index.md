---
title: ServicePointManager
second_title: Aspose.Slides för C++ API-referens
description: "Hanterar livscykelfaserna (skapa, underhålla och ta bort) för ServicePoint-klassinstanser. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 430
url: /sv/system.net/servicepointmanager/
---
## ServicePointManager klass


Hantera livscykelfaserna (skapa, underhålla och ta bort) av [ServicePoint](../servicepoint/) klassinstanser. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Omge alltid denna klass med [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ServicePointManager : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Hämtar en certifikatpolicy. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Hämtar ett värde som anger om certifikatet måste kontrolleras mot certifikatutfärdarens återkallningslista. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Hämtar det maximala antalet samtidiga anslutningar som tillåts av ServicePoint-class-instansern. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Hämtar en tidsgräns i millisekunder under vilken en DNS-upplösning anses vara giltig. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Hämtar ett värde som anger om en DNS-upplösning roterar bland de tillämpliga IP-adresserna. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Returnerar krypteringspolicyn som används av den aktuella instansen. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Hämtar ett värde som anger om ServicePoint-class-instanser använder 100-Continue-beteendet. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Hämtar den maximala inaktiva tiden för ServicePoint-class-instanser. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Hämtar det maximala antalet ServicePoint-class-instanser som kan hanteras av den aktuella instansen. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Hämtar ett värde som anger om utgångsanslutningssocklarna använder alternativet 'SO_REUSE_UNICASTPORT'. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Hämtar den säkerhetsprotokolltyp som används av ServicePoint-class-instanser som hanteras av den aktuella instansen. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Hämtar återanropet som används för att validera ett servercertifikat. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Hämtar ett värde som anger om ServicePoint-class-instanser använder Nagle-algoritmen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Ställer in en certifikatpolicy. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Ställer in ett värde som anger om certifikatet måste kontrolleras mot certifikatutfärdarens återkallningslista. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Ställer in det maximala antalet samtidiga anslutningar som tillåts av ServicePoint-class-instanser. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Ställer in en tidsgräns i millisekunder under vilken en DNS-upplösning anses vara giltig. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Ställer in ett värde som anger om en DNS-upplösning roterar bland de tillämpbara IP-adresserna. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Ställer in ett värde som anger om ServicePoint-class-instanser använder 100-Continue-beteendet. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Ställer in den maximala inaktiva tiden för ServicePoint-class-instanser. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Ställer in det maximala antalet ServicePoint-class-instanser som kan hanteras av den aktuella instansen. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Ställer in ett värde som anger om utgångsanslutningssocklarna använder alternativet 'SO_REUSE_UNICASTPORT'. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Ställer in den säkerhetsprotokolltyp som används av ServicePoint-class-instanser som hanteras av den aktuella instansen. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Ställer in återanropet som används för att validera ett servercertifikat. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Ställer in ett värde som anger om ServicePoint-class-instanser använder Nagle-algoritmen. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Ställer in värdet som anger om 'Keep-Alive'-alternativet är aktiverat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Standardantalet icke-persistenta anslutningar. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Standardantalet persistenta anslutningar. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Net](../)
* Bibliotek [Aspose.Slides](../../)