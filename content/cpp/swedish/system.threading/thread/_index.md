---
title: Thread
second_title: Aspose.Slides för C++ API-referens
description: "Trådamplementering. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 209
url: /sv/system.threading/thread/
---
## Trådklass


[Thread](./) implementation. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Thread : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Abort](./abort/)() | Avbryter tråden. Inte implementerad. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | Hämtar trådkultur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Hämtar objekt som beskriver aktuell tråd. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | Hämtar användargränssnittskultur som används av tråden. |
| **bool** [get_IsAlive](./get_isalive/)() | Kontrollerar om tråden är levande. |
| **bool** [get_IsBackground](./get_isbackground/)() | Kontrollerar om tråden är i bakgrunden. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Kontrollerar om tråden ägs av en trådpool. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | Hämtar identifierare för tråden. Kan hämtas från operativsystemet, men om OS-trådens identifierare överskrider int-gränser kan trådens id:n kollidera. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | Hämtar trådens namn. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | Hämtar trådens tillstånd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Hämtar identifierare för aktuell tråd. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| void [Interrupt](./interrupt/)() | Avbryter tråden. Inte implementerad. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Join](./join/)() | Ansluter till hanterad tråd. Utför obegränsad väntan om nödvändigt. |
| **bool** [Join](./join/)(int) | Ansluter till hanterad tråd. Utför begränsad väntan. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Ansluter till hanterad tråd. Utför begränsad väntan. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satset för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
| static void [MemoryBarrier](./memorybarrier/)() | Synkroniserar minnesåtkomst. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion i underklasser. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Kopierar TLS-data från en annan tråd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion i underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr per referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Sätter trådkultur. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Sätter användargränssnittskultur som tråden använder. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | Sätter tråden till bakgrund eller förgrund. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | Sätter trådens namn. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-:te mallargumentet till en weak-pekare (istället för shared). Tillåter att byta pekare i containrar till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| static void [Sleep](./sleep/)(int) | Stoppar aktuell tråd under angiven tidsgräns. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Stoppar aktuell tråd under angiven tidsgräns. |
| static void [SpinWait](./spinwait/)(int) | Väntar på ett specifikt antal loop-iterationer. |
| void [Start](./start/)() | Startar tråd med ett null-argumentobjekt. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Startar tråd. |
|  [Thread](./thread/)() | Konstruktor. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | Konstruktor. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Konstruktor. |
|  [Thread](./thread/)([Thread](./)\&) | Kopieringskonstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satset för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| static **bool** [Yield](./yield/)() | Gör ett yield på tråden. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
| virtual  [~Thread](./~thread/)() | Destruktor. |

## Anmärkningar

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
Denna kodexempel producerar följande utskrift:
Main thread ID: 2
Child thread ID: 1
*/
```

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)