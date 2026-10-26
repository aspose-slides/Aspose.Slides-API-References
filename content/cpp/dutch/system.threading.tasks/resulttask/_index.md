---
title: ResultTask
second_title: Aspose.Slides voor C++ API-referentie
description: Een Task-specialisatie die een resultaatwaarde retourneert bij voltooiing.
type: docs
weight: 40
url: /nl/system.threading.tasks/resulttask/
---
## ResultTask klasse


Een [Task](../task/) specialisatie die een resultaatwaarde retourneert bij voltooiing.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de resultaatwaarde die door de taak wordt geretourneerd. |
## Methoden

| Method | Description |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Activeert de taak voor uitvoering op een planner. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Voegt een voortzettingsactie toe die wordt uitgevoerd bij voltooiing. |
| void [Cancel](../task/cancel/)() | Markeert de taak als geannuleerd en beëindigt de taak. |
| void [Complete](./complete/)(const T\&) | Stelt de resultaatwaarde van de taak in en voltooit deze. |
| void [Complete](../task/complete/)() | Markeert de taak als voltooid en beëindigt de taak. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Configureert hoe wachtoperaties op deze resultataak zich moeten gedragen met betrekking tot contextvastlegging. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Maakt een voortzetting die wordt uitgevoerd wanneer de resultataak voltooid is. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Maakt een voortzetting die wordt uitgevoerd wanneer de resultataak voltooid is. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Maakt een voortzetting die wordt uitgevoerd wanneer de taak voltooid is. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Maakt een voortzetting die wordt uitgevoerd wanneer de taak voltooid is. |
| void [Deactivate](../task/deactivate/)() | Deactiveert de taak voor uitvoering op zijn huidige planner, indien aanwezig. |
| void [Dispose](../task/dispose/)() override | Vrijgeeft resources die aan de taak zijn gekoppeld. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-punt vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-punt vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| void [Execute](../task/execute/)() | Voert de functie van de taak uit. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Haalt het door de gebruiker gedefinieerde statusobject op dat aan de taak is gekoppeld. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Haalt een voltooide taak op (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Haalt de ID van de taak op. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Geeft aan of de taak is voltooid vanwege annulering. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Geeft aan of de taak is voltooid. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Geeft aan of de taak is voltooid vanwege een niet-afgehandelde uitzondering. |
| T [get_Result](./get_result/)() | Haalt het resultaat van de asynchrone bewerking op. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Haalt de planner op die aan deze taak is gekoppeld. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Haalt de huidige status van de taak op. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Haalt een awaiter op voor deze resultataak voor gebruik met Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt het hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-instructie vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste typen in. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiëringsconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, Initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt via referentie een valuetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Construeert een [ResultTask](./) met een functie die een waarde retourneert. |
|  [ResultTask](./resulttask/)() | Interne implementatie. Niet voor gebruik in gebruikerscode. |
|  [ResultTask](./resulttask/)(const T\&) | Interne constructor voor het maken van resultataak met opgegeven resultaat. |
| void [RunSynchronously](../task/runsynchronously/)() | Voert de taak synchroon uit op de huidige thread. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Voert de taak synchroon uit met de opgegeven planner. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Stelt de interne uit te voeren functie in. |
| void [set_Result](./set_result/)(const T\&) | Stelt de resultaatwaarde voor de taak in. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Stelt de planner in die aan deze taak is gekoppeld. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Stelt de taakstatus in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Start](../task/start/)() | Start de taakuitvoering met de standaard planner. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Start de taakuitvoering met de opgegeven planner. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Construeert een [Task](../task/) met een uit te voeren actie. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Construeert een [Task](../task/) met een actie en annulerings-token. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Construeert een [Task](../task/) met een stateful-actie en statusobject. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Construeert een [Task](../task/) met stateful-actie, status en annulerings-token. |
|  [Task](../task/task/)() | Interne constructor voor het maken van niet-geïnitialiseerde taken. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt conversie van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-instructie ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Wacht tot de taak voltooid is met annuleringsondersteuning. |
| void [Wait](../task/wait/)() | Wacht tot de taak voltooid is. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
|  [~Task](../task/~task/)() | Destructeur. |
## Opmerkingen



Stelt een asynchrone bewerking voor die een resultaat oplevert, vergelijkbaar met System.Threading.Tasks.Task<TResult> in .NET 
## Zie ook

* Klasse [Task](../task/)
* Naamruimte [System::Threading::Tasks](../)
* Bibliotheek [Aspose.Slides](../../)