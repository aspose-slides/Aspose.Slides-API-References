---
title: ResultTask
second_title: Aspose.Slides för C++ API-referens
description: En Task-specialisering som returnerar ett resultatvärde vid slutförande.
type: docs
weight: 40
url: /sv/system.threading.tasks/resulttask/
---
## ResultTask klass


En [Task](../task/) specialisering som returnerar ett resultatvärde vid slutförande.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av resultatvärdet som returneras av uppgiften |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktiverar uppgiften för körning på en schemaläggare. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Lägger till en fortsättningsåtgärd som ska utföras vid slutförande. |
| void [Cancel](../task/cancel/)() | Markerar uppgiften som avbruten och avslutar den. |
| void [Complete](./complete/)(const T\&) | Sätter resultatvärdet för uppgiften och slutför den. |
| void [Complete](../task/complete/)() | Markerar uppgiften som slutförd och avslutar den. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Konfigurerar hur väntan på detta resultatuppgift ska bete sig avseende kontextfångst. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Skapar en fortsättning som körs när resultatuppgiften slutförs. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Skapar en fortsättning som körs när resultatuppgiften slutförs. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Skapar en fortsättning som körs när resultatuppgiften slutförs. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Skapar en fortsättning som körs när resultatuppgiften slutförs. |
| void [Deactivate](../task/deactivate/)() | Inaktiverar uppgiften för körning på dess nuvarande schemaläggare, om någon. |
| void [Dispose](../task/dispose/)() override | Frigör resurser som är associerade med uppgiften. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| void [Execute](../task/execute/)() | Utför uppgiftens funktion. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Hämtar det användardefinierade tillståndsobjektet som är associerat med uppgiften. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Hämtar en slutförd uppgift (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Hämtar ID för uppgiften. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Hämtar om uppgiften avslutades på grund av avbrytning. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Hämtar om uppgiften har slutförts. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Hämtar om uppgiften avslutades på grund av ett ohanterat undantag. |
| T [get_Result](./get_result/)() | Hämtar resultatet av den asynkrona operationen. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Hämtar schemaläggaren som är associerad med denna uppgift. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Hämtar den aktuella statusen för uppgiften. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Hämtar en awaiter för detta resultatuppgift för användning med Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Konstruktar en [ResultTask](./) med en funktion som returnerar ett värde. |
|  [ResultTask](./resulttask/)() | Intern implementering. Inte avsedd för användarkod. |
|  [ResultTask](./resulttask/)(const T\&) | Intern konstruktor för att skapa resultatuppgifter med angivet resultat. |
| void [RunSynchronously](../task/runsynchronously/)() | Kör uppgiften synkront på den aktuella tråden. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Kör uppgiften synkront med den angivna schemaläggaren. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Sätter den interna funktionen som ska köras. |
| void [set_Result](./set_result/)(const T\&) | Sätter resultatvärdet för uppgiften. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Sätter schemaläggaren som är associerad med denna uppgift. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Sätter uppgiftsstatusen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Start](../task/start/)() | Startar uppgiftens körning med standard schemaläggare. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Startar uppgiftens körning med den angivna schemaläggaren. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Konstruktar en [Task](../task/) med en åtgärd att utföra. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruktar en [Task](../task/) med en åtgärd och en avbrytningstoken. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Konstruktar en [Task](../task/) med en tillståndsbevarande åtgärd och ett tillståndsobjekt. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruktar en [Task](../task/) med tillståndsbevarande åtgärd, tillstånd och avbrytningstoken. |
|  [Task](../task/task/)() | Intern konstruktor för att skapa oinitierade uppgifter. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Väntar på att uppgiften ska slutföras med stöd för avbrytning. |
| void [Wait](../task/wait/)() | Väntar på att uppgiften ska slutföras. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
|  [~Task](../task/~task/)() | Destruktor. |
## Anmärkningar



Representerar en asynkron operation som producerar ett resultat, liknande System.Threading.Tasks.Task<TResult> i .NET 
## Se även

* Klass [Task](../task/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)