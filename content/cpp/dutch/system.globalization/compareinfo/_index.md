---
title: CompareInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Voert cultuurgevoelige tekenreeksvergelijking uit. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een exemplaar van dit type op de stack of met de operator new, omdat dit leidt tot runtime-fouten en/of assertion-fouten. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 40
url: /nl/system.globalization/compareinfo/
---
## CompareInfo klasse

Voert cultuurgevoelige tekenreeksvergelijking uit. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met de operator new, omdat dit leidt tot runtime-fouten en/of assertion-fouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class CompareInfo : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Vergelijkt tekenreeksen. Niet geïmplementeerd. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Vergelijkt tekenreeksen. Alleen de modi Ordinal en OrdinalIgnoreCase worden ondersteund. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | Vergelijkt een gedeelte van de ene tekenreeks met een gedeelte van de tweede tekenreeks. Niet geïmplementeerd. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Vergelijkt het eindgedeelte van de ene tekenreeks met het eindgedeelte van de tweede tekenreeks met behulp van tekenreeksvergelijkingsmethoden. Niet geïmplementeerd. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | Vergelijkt het eindgedeelte van de ene tekenreeks met het eindgedeelte van de tweede tekenreeks. Niet geïmplementeerd. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Vergelijkt een gedeelte van de ene tekenreeks met een gedeelte van de tweede tekenreeks met behulp van tekenreeksvergelijkingsmethoden. Niet geïmplementeerd. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | RTTI-informatie. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met de C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| int [get_LCID](./get_lcid/)() const | Haalt het LCID op van de cultuur die aan de comparer is gekoppeld. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Haalt de naam op van de cultuur die aan de comparer is gekoppeld. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | Haalt informatie op over de sorteer-versie. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Haalt [CompareInfo](./) op die geassocieerd is met de opgegeven cultuur en gebruik maakt van tekenreeksvergelijkingsmethoden in de opgegeven assembly. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | Haalt [CompareInfo](./) op die geassocieerd is met de opgegeven cultuur en gebruik maakt van tekenreeksvergelijkingsmethoden in de opgegeven assembly. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | Haalt [CompareInfo](./) op die geassocieerd is met de opgegeven cultuur. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | Haalt [CompareInfo](./) op die geassocieerd is met de opgegeven cultuur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de gegevensstructuur voor referentieteller op die aan het object is gekoppeld. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Haalt tekenreeks-hashcode op op basis van de opgegeven vergelijkingsopties. |
| int [GetHashCode](./gethashcode/)() const override | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashing van aangepaste objecten in. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Haalt [SortKey](../sortkey/)-object op voor de opgegeven tekenreeks met de opgegeven vergelijkingsopties. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | Haalt [SortKey](../sortkey/)-object op voor de opgegeven tekenreeks. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Zoekt naar een substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Zoekt naar een substring. Alleen de modus Ordinal wordt ondersteund. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Zoekt naar een substring. Alleen de modus Ordinal wordt ondersteund. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Zoekt naar het opgegeven teken. Alleen de modus Ordinal wordt ondersteund. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Zoekt naar een substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | Zoekt naar het opgegeven teken. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Zoekt naar een substring. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Zoekt naar het opgegeven teken. Alleen de modus Ordinal wordt ondersteund. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Zoekt naar het opgegeven teken. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | Zoekt naar het opgegeven teken. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Zoekt naar een substring. Alleen de modus Ordinal wordt ondersteund. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Zoekt naar het opgegeven teken. Alleen de modus Ordinal wordt ondersteund. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Controleert of de opgegeven tekenreeks begint met het opgegeven voorvoegsel met behulp van de opgegeven vergelijkingsopties. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Controleert of de opgegeven tekenreeks begint met het opgegeven voorvoegsel. |
| static **bool** [IsSortable](./issortable/)(char16_t) | Controleert of een opgegeven teken sorteerbaar is. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | Controleert of een opgegeven tekenreeks sorteerbaar is. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Controleert of de opgegeven tekenreeks eindigt met het opgegeven achtervoegsel met behulp van de opgegeven vergelijkingsopties. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Controleert of de opgegeven tekenreeks eindigt met het opgegeven achtervoegsel. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | Zoekt de laatste voorkoming van de opgegeven substring. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van de opgegeven substring met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van het opgegeven teken met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | Zoekt de laatste voorkoming van de opgegeven tekenreeks. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van de opgegeven tekenreeks met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van het opgegeven teken met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | Zoekt de laatste voorkoming van de opgegeven tekenreeks. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | Zoekt de laatste voorkoming van het opgegeven teken. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van de opgegeven tekenreeks met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | Zoekt de laatste voorkoming van het opgegeven teken met de opgegeven vergelijkingsopties. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | Zoekt de laatste voorkoming van het opgegeven teken. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | Zoekt de laatste voorkoming van het opgegeven teken. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt klonen van aangepaste typen in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert simpelweg een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert simpelweg een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt conversie van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijgeeft alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)