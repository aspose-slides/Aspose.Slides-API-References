---
title: NameValueWithParametersHeaderValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een sleutel/waarde-paar met parameters voor dat in headers kan worden gebruikt. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Verpak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 183
url: /nl/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue klasse

Stelt een sleutel/waarde-paar met parameters voor die in headers kan worden gebruikt. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Verpak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het als argument aan functies door te geven.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\> [Find](../namevalueheadervalue/find/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, [String](../../system/string/)) | Zoekt de NameValueHeaderValue-class instantie in een collectie op basis van de opgegeven naam. |
| [String](../../system/string/) [get_Name](../namevalueheadervalue/get_name/)() | Retourneert de naam van de huidige instantie. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Retourneert parameters van de huidige instantie. |
| [String](../../system/string/) [get_Value](../namevalueheadervalue/get_value/)() | Haal een waarde op van de huidige instantie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| static **int32_t** [GetHashCode](../namevalueheadervalue/gethashcode/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | Retourneert een hash-code van alle items in de collectie. |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de [NameValueHeaderValue](../namevalueheadervalue/) klasse. |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de [NameValueHeaderValue](../namevalueheadervalue/) klasse. |
| static **int32_t** [GetNameValueListLength](../namevalueheadervalue/getnamevaluelistlength/)([String](../../system/string/), **int32_t**, char16_t, [System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar de collectie van NameValueHeaderValue-class instanties en retourneert de lengte van een geparseerde sub-tekenreeks. |
| static **int32_t** [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Converteert een opgegeven tekenreeks vanaf de gespecificeerde index naar een instantie van de [NameValueWithParametersHeaderValue](./) klasse. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| static **int32_t** [GetValueLength](../namevalueheadervalue/getvaluelength/)([String](../../system/string/), **int32_t**) | Retourneert de lengte van een waarde vanaf de gespecificeerde index. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven, representeert. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waakhond-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)() | Construeert een nieuwe instantie. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/), [String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/), [String](../../system/string/)) | Construeert een nieuwe instantie. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Construeert een nieuwe instantie. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiërende constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiërende constructie van subklassen mogelijk. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converteert een opgegeven tekenreeks naar een instantie van de [NameValueWithParametersHeaderValue](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de gespecificeerde waarde. |
| void [set_Value](../namevalueheadervalue/set_value/)([String](../../system/string/)) | Stelt een waarde in voor de huidige instantie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Stelt toe dat pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static void [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>) | Retourneert een stringrepresentatie van de collectie van NameValueHeaderValue-class instanties. |
| static [String](../../system/string/) [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**) | Retourneert een stringrepresentatie van de collectie van NameValueHeaderValue-class instanties. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\>\&) | Probeert een opgegeven tekenreeks te converteren naar een instantie van de [NameValueWithParametersHeaderValue](./) klasse. |
| static **bool** [TryParse](../namevalueheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | Probeert een opgegeven tekenreeks te converteren naar een instantie van de [NameValueHeaderValue](../namevalueheadervalue/) klasse. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waakhond-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [NameValueHeaderValue](../namevalueheadervalue/)
* Naamruimte [System::Net::Http::Headers](../)
* Bibliotheek [Aspose.Slides](../../)