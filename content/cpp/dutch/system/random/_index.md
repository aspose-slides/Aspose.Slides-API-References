---
title: Random
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een pseudo-willekeurige getalgenerator voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 1184
url: /nl/system/random/
---
## Random klasse


Stelt een pseudo-willekeurig getalgenerator voor. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/)-pointer en gebruik deze pointer om hem als argument door te geven aan functies.

```cpp
class Random : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Demonstreert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Demonstreert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analoge van C# 'is'-operator. |
| **bool** [IsNull](./isnull/)() const | Geeft altijd false terug. |
| void [Lock](../object/lock/)() | Implementeert de lock()-statement blokkering van C#. Roep direct aan of gebruik het [LockContext](../lockcontext/)-wachterobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| virtual **int32_t** [Next](./next/)() | Retourneert een niet-negatief willekeurig getal kleiner dan de maximale int32-waarde. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | Retourneert een niet-negatief willekeurig getal kleiner dan het opgegeven maximum. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | Retourneert een willekeurig getal binnen het opgegeven bereik. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Vult de elementen van het opgegeven byte-array met willekeurige getallen. |
| virtual **double** [NextDouble](./nextdouble/)() | Retourneert een willekeurig getal tussen 0,0 en 1,0. |
|  [Object](../object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
|  [Random](./random/)() | Initialiseert een nieuwe instantie met een tijd-afhankelijke standaard-zaadwaarde. |
|  [Random](./random/)(**int32_t**) | Initialiseert een nieuwe instantie van de [System.Random](./)-klasse met de opgegeven zaadwaarde. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object op referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in als een zwakke pointer (in plaats van een gedeelde). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analoge van C# [Object.ToString()](../object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert de C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/)-wachterobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
## Opmerkingen



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Verkrijg een willekeurig maandnummer en druk het af.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Vul de array met willekeurige getallen.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Druk de array af.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
Maand: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## Zie ook

* Klasse [Object](../object/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)