---
title: Monitor
second_title: Aspose.Slides voor C++ API-referentie
description: Klasse Monitor biedt een mechanisme dat de toegang tot objecten synchroniseert.
type: docs
weight: 157
url: /nl/system.threading/monitor/
---
## Monitor klasse

Klasse [Monitor](./) biedt een mechanisme dat de toegang tot objecten synchroniseert.

```cpp
class Monitor : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Verkrijgt een exclusieve lock op een opgegeven object. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Verkrijgt een exclusieve lock op het opgegeven object en stelt atomisch een waarde in die aangeeft of de lock is verkregen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl drijvende-kommag vergelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl drijvende-kommag vergelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Geeft een exclusieve lock op het opgegeven object vrij. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashberekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Bepaalt of de huidige thread de lock op het opgegeven object bezit. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, alleen initialiseert een nieuw object en maakt het mogelijk om subclasses te copy-construeren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, alleen initialiseert een nieuw object en maakt het mogelijk om subclasses te copy-construeren. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Notificeert een thread in de wachtende wachtrij van een wijziging in de status van het vergrendelde object. Niet geïmplementeerd. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Notificeert alle wachtende threads van een wijziging in de status van het object. Niet geïmplementeerd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Probeert een exclusieve lock op het opgegeven object te verkrijgen. Niet geïmplementeerd. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Probeert een exclusieve lock op het opgegeven object te verkrijgen en stelt atomisch een waarde in die aangeeft of de lock is verkregen. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Probeert, voor het opgegeven aantal milliseconden, een exclusieve lock op het opgegeven object te verkrijgen. Niet geïmplementeerd. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen. Niet geïmplementeerd. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen en stelt atomisch een waarde in die aangeeft of de lock is verkregen. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | Probeert, voor de opgegeven tijdsduur, een exclusieve lock op het opgegeven object te verkrijgen en stelt atomisch een waarde in die aangeeft of de lock is verkregen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | Geeft de lock op een object vrij en blokkeert de huidige thread totdat deze de lock opnieuw verkrijgt. Als het opgegeven time-out-interval verstrijkt, gaat de thread naar de klaar-queue. Optioneel verlaat het synchronisatiedomein voor de gesynchroniseerde context vóór het wachten en verwerft het domein daarna opnieuw. Niet geïmplementeerd. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | Geeft de lock op een object vrij en blokkeert de huidige thread totdat deze de lock opnieuw verkrijgt. Als het opgegeven time-out-interval verstrijkt, gaat de thread naar de klaar-queue. Optioneel verlaat het synchronisatiedomein voor de gesynchroniseerde context vóór het wachten en verwerft het domein daarna opnieuw. Niet geïmplementeerd. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Geeft de lock op een object vrij en blokkeert de huidige thread totdat deze de lock opnieuw verkrijgt. Als het opgegeven time-out-interval verstrijkt, gaat de thread naar de klaar-queue. Niet geïmplementeerd. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Geeft de lock op een object vrij en blokkeert de huidige thread totdat deze de lock opnieuw verkrijgt. Als het opgegeven time-out-interval verstrijkt, gaat de thread naar de klaar-queue. Niet geïmplementeerd. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Geeft de lock op een object vrij en blokkeert de huidige thread totdat deze de lock opnieuw verkrijgt. Niet geïmplementeerd. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
## Opmerkingen

```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
Dit codevoorbeeld geeft de volgende uitvoer:
Threads count: 3
Thread 0: 1
Thread 0: 2
Thread 0: 3
Thread 0: 4
Thread 0: 5
Thread 1: 1
Thread 1: 2
Thread 1: 3
Thread 1: 4
Thread 1: 5
Thread 2: 1
Thread 2: 2
Thread 2: 3
Thread 2: 4
Thread 2: 5
*/
```

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)