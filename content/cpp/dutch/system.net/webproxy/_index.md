---
title: WebProxy
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een http-webproxyserver. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 495
url: /nl/system.net/webproxy/
---
## WebProxy klasse


Vertegenwoordigt een http web-proxy server. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit resulteert in runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Haalt het adres van de huidige proxy-server op. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_BypassList](./get_bypasslist/)() | Haalt de lijst met adressen op die de proxy-server niet gebruiken. |
| **bool** [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Retourneert een waarde die aangeeft of de proxy-server moet worden gebruikt voor lokale adressen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | Haal de referenties op die naar de proxy-server worden gestuurd voor authenticatie. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Retourneert een waarde die aangeeft of de standaardreferenties met verzoeken moeten worden meegestuurd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebProxy](./)\> [GetDefaultProxy](./getdefaultproxy/)() | Retourneert de proxy die de niet-dynamische instellingen van Internet Explorer gebruikt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [GetProxy](./getproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Retourneert de geproxiede URI voor een webverzoek. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschrijft dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| virtual **bool** [IsBypassed](./isbypassed/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Controleert of de proxy-server niet wordt gebruikt voor de opgegeven URI. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Stelt het adres van de huidige proxy-server in. |
| void [set_BypassList](./set_bypasslist/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Stelt de lijst met adressen in die de proxy-server niet gebruiken. |
| void [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(**bool**) | Stelt een waarde in die aangeeft of de proxy-server moet worden gebruikt voor lokale adressen. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Stelt de referenties in die naar de proxy-server worden gestuurd voor authenticatie. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | Stelt een waarde in die aangeeft of de standaardreferenties met verzoeken moeten worden meegestuurd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [WebProxy](./webproxy/)() | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **int32_t**) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Construeert een nieuwe instantie. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Construeert een nieuwe instantie. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [IWebProxy](../iwebproxy/)
* Naamruimte [System::Net](../)
* Library [Aspose.Slides](../../)