---
title: Object
second_title: Aspose.Slides voor C++ API-referentie
description: Basisklasse die het mogelijk maakt methoden die beschikbaar zijn voor de System.Object-klasse in C# te gebruiken. Alle niet-triviale klassen die in de vertaalde omgeving worden gebruikt, moeten hiervan overerven.
type: docs
weight: 1132
url: /nl/system/object/
---
## Objectklasse

Basisklasse die het mogelijk maakt methoden die beschikbaar zijn voor de [System.Object](./)-klasse in C# te gebruiken. Alle niet-triviale klassen die in de vertaalde omgeving worden gebruikt, moeten hiervan overerven.

```cpp
class Object
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](./equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijkingen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijkingen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](./gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](./gettype/)-aanroep. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven, vertegenwoordigt. Analoge van de C# 'is'-operator. |
| void [Lock](./lock/)() | Implementeert vergrendeling van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](./memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](./object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](./object/)([Object](./) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object via referentie met nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](./referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](./referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers over te schakelen naar zwakke modus. |
| int [SharedCount](./sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Vergroot de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Verkleint en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analoge van de C# [Object.ToString()](./tostring/)-methode. Maakt conversie van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementeert het C# typeof([System.Object](./))-construct. |
| void [Unlock](./unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Vergroot de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Verkleint de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](./~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ptr](./ptr/) | Alias voor smart pointer type. |

## Opmerkingen

Naast de methoden die beschikbaar zijn in de C# [System.Object](./)-klasse, biedt het ook ondersteuning voor enkele concepten die specifiek zijn voor de vertaalde code-omgeving. Dit omvat referentietelling die wordt gebruikt door slimme-pointer-klassen ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) en andere diensten gerelateerd aan geheugenbeheer, debuggen, enz.

Elk [Object](./) heeft twee referentietellers: een gedeelde referentieteller en een zwakke referentieteller. De zwakke referentieteller wordt altijd opgeslagen in een losgekoppelde datastructuur in plaats van in [Object](./) zelf, waardoor zwakke pointers langer blijven bestaan dan het referentie-object. De slimme referentieteller wordt opgeslagen ofwel in het object zelf of in dezelfde losgekoppelde structuur, afhankelijk van de staat van de macro ENABLE_EXTERNAL_REFCOUNT. Standaard is deze ingeschakeld in debug-builds en uitgeschakeld in release-builds. Als de slimme-pointer-teller in het object zelf wordt opgeslagen, wordt de losgekoppelde datastructuur alleen aangemaakt als er zwakke pointers naar het object bestaan. Anders wordt deze samen met het object zelf aangemaakt.

Alle slimme pointers gebruiken deze twee referentietellers en dragen bij aan dezelfde, enige eigendomsgroep.

Als een [Object](./)-subklasse op de stack wordt aangemaakt, mogen er geen slimme pointers naar worden gemaakt; anders ontstaat er een probleem bij het verwijderen van de stack.

Dit type kan worden gealloceerd op de stack als waardetype of op de heap met de [System::MakeObject()](../makeobject/)-functie. Zodra het object is gealloceerd, mag men deze twee gebruikssituaties nooit door elkaar halen: het hebben van [SmartPtr](../smartptr/)-pointers naar op de stack gealloceerde objecten is strikt verboden.

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)