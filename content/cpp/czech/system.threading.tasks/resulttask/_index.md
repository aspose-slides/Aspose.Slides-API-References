---
title: ResultTask
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Specializace úlohy, která po dokončení vrací hodnotu výsledku.
type: docs
weight: 40
url: /cs/system.threading.tasks/resulttask/
---
## ResultTask třída


Specializace [Task](../task/), která po dokončení vrací hodnotu výsledku.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty výsledku vrácené úlohou |
## Metody

| Metoda | Popis |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktivuje úlohu k provedení na plánovači. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Přidá akci pokračování, která se provede po dokončení. |
| void [Cancel](../task/cancel/)() | Označí úlohu jako zrušenou a ukončí úlohu. |
| void [Complete](./complete/)(const T\&) | Nastaví hodnotu výsledku pro úlohu a dokončí ji. |
| void [Complete](../task/complete/)() | Označí úlohu jako dokončenou a ukončí úlohu. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Nastavuje, jak by měly await operace na této úloze s výsledkem fungovat ohledně zachycení kontextu. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Vytvoří pokračování, které se spustí, když se úloha s výsledkem dokončí. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Vytvoří pokračování, které se spustí, když se úloha s výsledkem dokončí. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Vytvoří pokračování, které se spustí, když se úloha dokončí. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Vytvoří pokračování, které se spustí, když se úloha dokončí. |
| void [Deactivate](../task/deactivate/)() | Deaktivuje úlohu pro provedení na jejím aktuálním plánovači, pokud existuje. |
| void [Dispose](../task/dispose/)() override | Uvolní prostředky spojené s úlohou. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| void [Execute](../task/execute/)() | Spustí funkci úlohy. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Získá uživatelem definovaný stavový objekt spojený s úlohou. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Získá dokončenou úlohu (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Získá ID úlohy. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Získá, zda úloha byla dokončena kvůli zrušení. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Získá, zda úloha byla dokončena. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Získá, zda úloha byla dokončena kvůli neodchycené výjimce. |
| T [get_Result](./get_result/)() | Získá výsledek asynchronní operace. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Získá plánovač spojený s touto úlohou. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Získá aktuální stav úlohy. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Získá awaiter pro tuto úlohu s výsledkem k použití s Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstrukcí podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstrukcí podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Vytvoří [ResultTask](./) s funkcí, která vrací hodnotu. |
|  [ResultTask](./resulttask/)() | Interní implementace. Není určena pro uživatelský kód. |
|  [ResultTask](./resulttask/)(const T\&) | Interní konstruktor pro vytvoření úloh s výsledkem se zadaným výsledkem. |
| void [RunSynchronously](../task/runsynchronously/)() | Spustí úlohu synchronně na aktuálním vlákně. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Spustí úlohu synchronně pomocí zadaného plánovače. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Nastaví interní funkci k provedení. |
| void [set_Result](./set_result/)(const T\&) | Nastaví hodnotu výsledku pro úlohu. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Nastaví plánovač spojený s touto úlohou. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Nastaví stav úlohy. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Start](../task/start/)() | Spustí provádění úlohy pomocí výchozího plánovače. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Spustí provádění úlohy pomocí zadaného plánovače. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Vytvoří [Task](../task/) s akcí k provedení. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Vytvoří [Task](../task/) s akcí a tokenem zrušení. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Vytvoří [Task](../task/) se stavovou akcí a stavovým objektem. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Vytvoří [Task](../task/) se stavovou akcí, stavem a tokenem zrušení. |
|  [Task](../task/task/)() | Interní konstruktor pro vytvoření neinicializovaných úloh. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Čeká na dokončení úlohy s podporou zrušení. |
| void [Wait](../task/wait/)() | Čeká na dokončení úlohy. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
|  [~Task](../task/~task/)() | Destruktor. |
## Poznámky

Představuje asynchronní operaci, která produkuje výsledek, podobně jako System.Threading.Tasks.Task<TResult> v .NET 
## Viz také

* Třída [Task](../task/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)