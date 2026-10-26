---
title: "System::Threading::Tasks"
second_title: "Aspose.Slides C++ API referenciája"
description: 
type: docs
weight: 1015
url: /hu/system.threading.tasks/
---
## Osztályok

| Class | Description |
| --- | --- |
| [Parallel](./parallel/) | Támogatást biztosít a párhuzamos ciklusokhoz és régiókhoz. |
| [ParallelLoopResult](./parallelloopresult/) | Biztosítja egy [Parallel](./parallel/) ciklus befejezési állapotát. |
| [ParallelOptions](./paralleloptions/) | Tárolja az opciókat, amelyek a [Parallel](./parallel/) osztály metódusainak működését konfigurálják. |
| [ResultTask](./resulttask/) | Egy [Task](./task/) specializáció, amely a befejezéskor visszaad egy eredményértéket. |
| [ResultValueTask](./resultvaluetask/) | Képvisel egy hibrid, feladathoz hasonló típust, amely közvetlen eredményértéket vagy egy ResultTask<T>-t is befoglalhat. |
| [Task](./task/) | Képvisel egy aszinkron műveletet, amelyre várakozhatunk és más feladatokkal összefűzhető. |
| [TaskScheduler](./taskscheduler/) | Képvisel egy objektumot, amely kezeli a feladatok szálakra sorba állításának alacsony szintű munkáját. |
| [ValueTask](./valuetask/) | Biztosít egy várakoztatható eredményt egy aszinkron művelethez. |
## Függvények

| Function | Description |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Létrehoz egy feladatot, amely egy idő késleltetés után befejeződik. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Létrehoz egy feladatot, amely egy idő késleltetés után befejeződik, és leállítható. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Létrehoz egy feladatot, amely a megadott tokennel történő leállítás miatt befejeződött. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Létrehoz egy feladatot, amely a megadott kivétellel befejeződött. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Létrehoz egy feladatot, amely a megadott kivétellel és eredménytípussal befejeződött. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Létrehoz egy feladatot, amely a megadott eredménnyel sikeresen befejeződött. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | A megadott munkát a szálkészletben futtatásra sorolja, és egy [Task](./task/) kezelőt ad vissza a munkához. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | A megadott munkát a szálkészletben futtatásra sorolja, és egy [Task](./task/) kezelőt ad vissza a munkához. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | A megadott munkát a szálkészletben futtatásra sorolja, és egy proxy-t ad vissza a függvény által visszaadott [Task](./task/)-hoz. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | A megadott munkát a szálkészletben futtatásra sorolja, és egy Task<TResult> kezelőt ad vissza a munkához. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Várja, amíg az összes megadott [Task](./task/) objektum befejeződik. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Várja, amíg az összes megadott [Task](./task/) objektum befejeződik. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Várja, amíg a megadott [Task](./task/) objektumok bármelyike befejeződik. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Várja, amíg a megadott [Task](./task/) objektumok bármelyike befejeződik. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződött. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződött. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződött. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor az összes megadott feladat befejeződött. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor a megadott feladatok bármelyike befejeződik. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor a megadott feladatok bármelyike befejeződik. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor a megadott feladatok bármelyike befejeződik. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Létrehoz egy feladatot, amely akkor fejeződik be, amikor a megadott feladatok bármelyike befejeződik. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Létrehoz egy várakoztatható feladatot, amely aszinkron módon visszaadja a vezérlést a jelenlegi kontextusba, amikor várakoznak rá. |
## Felsorolások

| Enum | Description |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |