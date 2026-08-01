---
title: ContentRangeHeaderValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een waarde van de 'Content-Range' header voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wrap altijd deze klasse in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 40
url: /nl/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue klasse

Stelt een waarde van de 'Content-Range' header voor. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assert-fouten oplevert. Wrap altijd deze klasse in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**, **int64_t**) | Construeert een nieuw exemplaar. |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**) | Construeert een nieuw exemplaar. |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**) | Construeert een nieuw exemplaar. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommapuntvergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommapuntvergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_From](./get_from/)() | Haalt een positie op waarop het verzenden van data moet beginnen. |
| **bool** [get_HasLength](./get_haslength/)() const | Haalt een waarde op die aangeeft of de lengte is gespecificeerd voor de huidige header. |
| **bool** [get_HasRange](./get_hasrange/)() const | Haalt een waarde op die aangeeft of het bereik is gespecificeerd voor de huidige header. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Length](./get_length/)() | Haalt de lengte van een entity-body op. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_To](./get_to/)() | Haalt een positie op waarop het verzenden van data moet stoppen. |
| [String](../../system/string/) [get_Unit](./get_unit/)() | Haalt de eenheden op die in het bereik worden gebruikt. |
| static **int32_t** [GetContentRangeLength](./getcontentrangelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Converteert een opgegeven string vanaf de gespecificeerde positie naar een instantie van de [ContentRangeHeaderValue](./) klasse. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analog van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converteert een opgegeven string naar een instantie van de [ContentRangeHeaderValue](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Unit](./set_unit/)([String](../../system/string/)) | Stelt de eenheden in die in het bereik worden gebruikt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers om te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt omzetten van aangepaste objecten naar string mogelijk. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\>\&) | Probeert een opgegeven string naar een instantie van de [ContentRangeHeaderValue](./) klasse te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |
## Zie ook

* Klasse [ICloneable](../../system/icloneable/)
* Naamruimte [System::Net::Http::Headers](../)
* Bibliotheek [Aspose.Slides](../../)