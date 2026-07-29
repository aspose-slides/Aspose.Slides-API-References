---
title: ParallelOptions
second_title: Aspose.Slides för C++ API-referens
description: Lagrar alternativ som konfigurerar operationen av metoder på Parallel-klassen.
type: docs
weight: 27
url: /sv/system.threading.tasks/paralleloptions/
---
## ParallelOptions klass

Lagrar alternativ som konfigurerar operationen av metoder på [Parallel](../parallel/) klass.

```cpp
class ParallelOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C# stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C# stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C# stil jämförelse av flyttal där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C# stil jämförelse av dubbelprecision där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| const [CancellationToken](../../system.threading/cancellationtoken/)\& [get_CancellationToken](./get_cancellationtoken/)() | Hämtar [CancellationToken](../../system.threading/cancellationtoken/) som är associerad med denna [ParallelOptions](./) instans. |
| **int32_t** [get_MaxDegreeOfParallelism](./get_maxdegreeofparallelism/)() | Hämtar maximalt antal parallella operationer som är aktiverat för denna [ParallelOptions](./) instans. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_TaskScheduler](./get_taskscheduler/)() | Hämtar [TaskScheduler](../taskscheduler/) som är associerad med denna [ParallelOptions](./) instans. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar datastrukturen för referensräknare som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Gör det möjligt att hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopierande av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopierande av underklasser. |
|  [ParallelOptions](./paralleloptions/)() | Konstruerar en [ParallelOptions](./)-instans med standardvärden. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CancellationToken](./set_cancellationtoken/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Sätter [CancellationToken](../../system.threading/cancellationtoken/) som är associerad med denna [ParallelOptions](./) instans. |
| void [set_MaxDegreeOfParallelism](./set_maxdegreeofparallelism/)(**int32_t**) | Sätter maximalt antal parallella operationer som är aktiverat för denna [ParallelOptions](./) instans. |
| void [set_TaskScheduler](./set_taskscheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Sätter [TaskScheduler](../taskscheduler/) som är associerad med denna [ParallelOptions](./) instans. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)