---
title: ProductHeaderValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een producttoken voor in een waarde van de 'User-Agent' header. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit zal resulteren in runtime fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 209
url: /nl/system.net.http.headers/productheadervalue/
---
## ProductHeaderValue klasse

Stelt een producttoken voor in een waarde van de 'User-Agent' header. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit zal resulteren in runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class ProductHeaderValue : public System::ICloneable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [String](../../system/string/) [get_Name](./get_name/)() | Retourneert de producttoken-naam. |
| [String](../../system/string/) [get_Version](./get_version/)() | Retourneert de producttoken-versie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hash-en van aangepaste objecten mogelijk. |
| static **int32_t** [GetProductLength](./getproductlength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](./)\>\&) | Converteert een doorgegeven string vanaf de opgegeven index naar een instantie van de [ProductHeaderValue](./) klasse. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschrijft dat door targetType wordt beschreven. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock() instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converteert een doorgegeven string naar een instantie van de [ProductHeaderValue](./) klasse. |
|  [ProductHeaderValue](./productheadervalue/)([String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [ProductHeaderValue](./productheadervalue/)([String](../../system/string/), [String](../../system/string/)) | Construeert een nieuwe instantie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Hiermee kun je pointers in containers naar zwakke modus schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](./)\>\&) | Probeert een doorgegeven string te converteren naar een instantie van de [ProductHeaderValue](./) klasse. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Bibliotheek [Aspose.Slides](../../)