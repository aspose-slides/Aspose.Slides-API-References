---
title: ResultTask
second_title: Aspose.Slides for C++ API-referencia
description: Egy Task specializáció, amely a befejezéskor egy eredményértéket ad vissza.
type: docs
weight: 40
url: /hu/system.threading.tasks/resulttask/
---
## ResultTask osztály


A [Task](../task/) specializáció, amely a befejezéskor egy eredményértéket ad vissza.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A feladat által visszaadott eredményérték típusa |
## Metódusok

| Method | Description |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktiválja a feladatot a végrehajtáshoz egy ütemezőn. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Hozzáad egy folytatás műveletet, amely a befejezéskor kerül végrehajtásra. |
| void [Cancel](../task/cancel/)() | Megjelöli a feladatot töröltként, és befejezi a feladatot. |
| void [Complete](./complete/)(const T\&) | Beállítja a feladat eredményértékét, és befejezi azt. |
| void [Complete](../task/complete/)() | Megjelöli a feladatot befejezettként, és befejezi a feladatot. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Beállítja, hogyan viselkedjenek a várakozások ezen az eredményfeladaton a kontextus rögzítése tekintetében. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Létrehoz egy folytatást, amely a feladat eredménye megtörténtekor végrehajtódik. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Létrehoz egy folytatást, amely a feladat eredménye megtörténtekor végrehajtódik. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Létrehoz egy folytatást, amely a feladat eredménye megtörténtekor végrehajtódik. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Létrehoz egy folytatást, amely a feladat eredménye megtörténtekor végrehajtódik. |
| void [Deactivate](../task/deactivate/)() | Kikapcsolja a feladatot a jelenlegi ütemezőn történő végrehajtásra, ha van. |
| void [Dispose](../task/dispose/)() override | Felszabadítja a feladathoz kapcsolódó erőforrásokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| void [Execute](../task/execute/)() | Végrehajtja a feladat függvényét. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Lekéri a feladathoz kapcsolódó felhasználó által definiált állapotobjektumot. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Lekéri egy befejezett feladatot (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Lekéri a feladat azonosítóját. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Megmondja, a feladat megszakítás miatt fejeződött-e be. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Megmondja, befejeződött-e a feladat. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Megmondja, a feladat nem kezelt kivétel miatt fejeződött-e be. |
| T [get_Result](./get_result/)() | Lekéri az aszinkron művelet eredményét. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Lekéri a feladathoz társított ütemezőt. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Lekéri a feladat aktuális állapotát. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Lekéri egy awaitert ehhez az eredményfeladathoz, amely Az Await használatával használható. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | [ResultTask](./) objektumot hoz létre egy értéket visszaadó függvénnyel. |
|  [ResultTask](./resulttask/)() | Belső megvalósítás. Nem felhasználói kódnak szánt. |
|  [ResultTask](./resulttask/)(const T\&) | Belső konstruktor meghatározott eredménnyel rendelkező eredményfeladatok létrehozásához. |
| void [RunSynchronously](../task/runsynchronously/)() | Fut a feladat szinkron módon az aktuális szálon. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Fut a feladat szinkron módon a megadott ütemezővel. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Beállítja a végrehajtandó belső függvényt. |
| void [set_Result](./set_result/)(const T\&) | Beállítja a feladat eredményértékét. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Beállítja a feladathoz társított ütemezőt. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Beállítja a feladat állapotát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge pointerként (nem megosztottként) állítja be. Lehetővé teszi a konténerekben lévő pointerek gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti a megosztott referenciaszámlálót és visszaadja azt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Start](../task/start/)() | Elindítja a feladat végrehajtását az alapértelmezett ütemezővel. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Elindítja a feladat végrehajtását a megadott ütemezővel. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | [Task](../task/) objektumot hoz létre egy végrehajtandó művelettel. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | [Task](../task/) objektumot hoz létre egy művelettel és egy leállítási tokennel. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | [Task](../task/) objektumot hoz létre állapotot tároló művelettel és állapotobjektummal. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | [Task](../task/) objektumot hoz létre állapotot tároló művelettel, állapottal és leállítási tokennel. |
|  [Task](../task/task/)() | Belső konstruktor nem inicializált feladatok létrehozásához. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Várja a feladat befejezését leállítási támogatással. |
| void [Wait](../task/wait/)() | Várja a feladat befejezését. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
|  [~Task](../task/~task/)() | Megsemmisítő. |
## Megjegyzés



Egy aszinkron műveletet képvisel, amely eredményt termel, hasonló a .NET System.Threading.Tasks.Task<TResult>-hez. 
## Kapcsolódó

* Osztály [Task](../task/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)