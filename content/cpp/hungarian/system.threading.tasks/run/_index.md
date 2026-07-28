---
title: Run()
second_title: Aspose.Slides C++ API referencia
description: A megadott feladatot a szálkészletben futtatásra sorolja be, és visszaad egy Task kezelőt ehhez a feladathoz.
type: docs
weight: 157
url: /hu/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) függvény

A megadott feladatot a szálkészletben futtatásra sorolja be, és visszaad egy [Task](../task/) kezelőt ehhez a feladathoz.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Az aszinkron módon végrehajtandó feladat. |

### Visszatérési érték

Egy [Task](../task/), amely a szálkészletben végrehajtásra sorolt feladatot képviseli.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) függvény

A megadott feladatot a szálkészletben futtatásra sorolja be, és visszaad egy [Task](../task/) kezelőt ehhez a feladathoz.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Az aszinkron módon végrehajtandó feladat. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Egy leállítási token, amely felhasználható a feladat leállítására, ha az még nem indult el. |

### Visszatérési érték

Egy [Task](../task/), amely a szálkészletben végrehajtásra sorolt feladatot képviseli.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) függvény

A megadott feladatot a szálkészletben futtatásra sorolja be, és visszaad egy proxy-t a függvény által visszaadott [Task](../task/) számára.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Az aszinkron módon végrehajtandó feladat, amely egy [Task](../task/) értéket ad vissza. |

### Visszatérési érték

Egy [Task](../task/), amely a függvény által visszaadott [Task](../task/) proxy-ját jelenti.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) függvény

A megadott feladatot a szálkészletben futtatásra sorolja be, és visszaad egy Task<TResult> kezelőt ehhez a feladathoz.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TResult | A feladat által visszaadott eredmény típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Az aszinkron módon végrehajtandó feladat. |

### Visszatérési érték

Egy Task<TResult>, amely a szálkészletben végrehajtásra sorolt feladatot képviseli.

## Lásd még

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Osztály [CancellationToken](../../system.threading/cancellationtoken/)
* Osztály [Func](../../system/func/)
* Névterület [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)