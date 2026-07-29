---
title: AutoResetEvent
second_title: Aspose.Slides för C++ API-referens
description: "Händelse för att meddela väntande tråd att den återställs automatiskt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendesfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.threading/autoresetevent/
---
## AutoResetEvent klass

Event för att meddela väntande tråd att återställs automatiskt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendesfel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AutoResetEvent : public System::Threading::EventWaitHandle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [AutoResetEvent](./autoresetevent/)(**bool**) | Konstruktor. |
| virtual void [Close](../waithandle/close/)() | Frigir alla resurser som är associerade med handtaget. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
|  [EventWaitHandle](../eventwaithandle/eventwaithandle/)(**bool**, [EventResetMode](../eventresetmode/)) | Konstruktor. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [wait_handle_t](../wait_handle_t/) [get_Handle](../waithandle/get_handle/)() | Hämtar handtag. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual **bool** [Reset](../eventwaithandle/reset/)() | Sätter händelsen i icke-signalerande tillstånd. |
| virtual **bool** [Set](../eventwaithandle/set/)() | Sätter händelsen i signalerande tillstånd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-satsss utlåsning. Anropas direkt eller via [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Väntar på att alla handtag ska avfyras. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Väntar på att alla handtag ska avfyras. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Väntar på att alla handtag ska avfyras. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | Väntar på att någon av handtagen ska avfyras. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | Väntar på att någon av handtagen ska avfyras. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | Väntar på att någon av handtagen ska avfyras. |
| virtual **bool** [WaitOne](../waithandle/waitone/)() | Väntar på att handtaget ska avfyras under obegränsad tid. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int) | Väntar på att handtaget ska avfyras. |
| virtual **bool** [WaitOne](../waithandle/waitone/)([TimeSpan](../../system/timespan/)) | Väntar på att handtaget ska avfyras. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int, **bool**) | Väntar på att handtaget ska avfyras. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [~EventWaitHandle](../eventwaithandle/~eventwaithandle/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
| virtual  [~WaitHandle](../waithandle/~waithandle/)() | Destruktor. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Speciellt värde som returneras av funktionen, annars returneras index för signalerat objekt i arrayen om timeout överskrids och inget signalerar. |

## Anmärkningar

```cpp
#include "system/threading/auto_reset_event.h"
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

  auto autoResetEvent = System::MakeObject<AutoResetEvent>(true);
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &autoResetEvent]() -> void {
      autoResetEvent->WaitOne();
      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }
      autoResetEvent->Set();
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
Det här kodexemplet producerar följande utskrift:
Antal trådar: 3
Tråd 0: 1
Tråd 0: 2
Tråd 0: 3
Tråd 0: 4
Tråd 0: 5
Tråd 1: 1
Tråd 1: 2
Tråd 1: 3
Tråd 1: 4
Tråd 1: 5
Tråd 2: 1
Tråd 2: 2
Tråd 2: 3
Tråd 2: 4
Tråd 2: 5
*/
```

## Se även

* Klass [EventWaitHandle](../eventwaithandle/)
* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)