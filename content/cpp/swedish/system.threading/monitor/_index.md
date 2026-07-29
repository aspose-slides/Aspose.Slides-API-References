---
title: Monitor
second_title: Aspose.Slides för C++ API-referens
description: Klassen Monitor tillhandahåller en mekanism som synkroniserar åtkomst till objekt.
type: docs
weight: 157
url: /sv/system.threading/monitor/
---
## Monitor-klass


Klassen [Monitor](./) tillhandahåller en mekanism som synkroniserar åtkomst till objekt.

```cpp
class Monitor : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Erhåller ett exklusivt lås på ett specificerat objekt. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Erhåller ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika något värde, inklusive NaN. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Släpper ett exklusivt lås på det specificerade objektet. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiskt typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Avgör om den aktuella tråden har låset på det specificerade objektet. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Meddelar en tråd i vänteskön om en förändring i det låsta objektets tillstånd. Ej implementerad. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Meddelar alla väntande trådar om en förändring i objektets tillstånd. Ej implementerad. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Försöker erhålla ett exklusivt lås på det specificerade objektet. Ej implementerad. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Försöker erhålla ett exklusivt lås på det specificerade objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Försöker, under det angivna antalet millisekunder, erhålla ett exklusivt lås på det specifika objektet. Ej implementerad. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Försöker, under den angivna tidsmängden, erhålla ett exklusivt lås på det specifika objektet. Ej implementerad. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | Försöker, under den angivna tidsmängden, erhålla ett exklusivt lås på det specifika objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | Försöker, under den angivna tidsmängden, erhålla ett exklusivt lås på det specifika objektet och sätter atomärt ett värde som indikerar om låset togs. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den angivna tidsgränsen löper ut går tråden in i klarköen. Eventuellt lämnar den synkroniseringsdomänen för det synkroniserade sammanhanget före väntan och återtar domänen efteråt. Ej implementerad. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den angivna tidsgränsen löper ut går tråden in i klarköen. Eventuellt lämnar den synkroniseringsdomänen för det synkroniserade sammanhanget före väntan och återtar domänen efteråt. Ej implementerad. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den angivna tidsgränsen löper ut går tråden in i klarköen. Ej implementerad. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om den angivna tidsgränsen löper ut går tråden in i klarköen. Ej implementerad. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Ej implementerad. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |
## Anmärkningar



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
Detta kodexempel producerar följande utskrift:
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

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)