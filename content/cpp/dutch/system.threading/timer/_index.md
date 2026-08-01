---
title: Timer
second_title: Aspose.Slides voor C++ API-referentie
description: "Timer-klasse die een taakitem uitvoert in een afzonderlijke thread na vertraging. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit zal leiden tot runtime fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 248
url: /nl/system.threading/timer/
---
## Timerklasse

[Timer](./) klasse die een taakitem uitvoert in een afzonderlijke thread na vertraging. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class Timer : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Change](./change/)(**int64_t**, **int64_t**) | Plant de timer opnieuw of annuleert deze. |
| **bool** [Change](./change/)([System::TimeSpan](../../system/timespan/), [System::TimeSpan](../../system/timespan/)) | Plant de timer opnieuw of annuleert deze. |
| void [Dispose](./dispose/)() | Plant de timer uit. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-gegevensstructuur geassocieerd met het object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Verwijst-vergelijkt waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [Timer](./timer/)([TimerCallback](../timercallback/)) | Constructor. |
|  [Timer](./timer/)([TimerCallback](../timercallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, **int64_t**, **int64_t**) | Constructor. |
|  [Timer](./timer/)([TimerCallback](../timercallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, [System::TimeSpan](../../system/timespan/), [System::TimeSpan](../../system/timespan/)) | Constructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Opmerkingen

```cpp
#include "system/threading/thread.h"
#include "system/threading/timer.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  using namespace System::Threading;

  auto number = 0;
  auto timer = System::MakeObject<Timer>([&number](System::SharedPtr<System::Object> object) -> void {
    std::cout << ++number << std::endl;
  }, nullptr, 0, 200);

  Thread::Sleep(1000);
  timer->Dispose();

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
1
2
3
4
5
*/
```

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)