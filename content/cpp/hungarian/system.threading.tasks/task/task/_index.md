---
title: Task()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy Task objektumot egy végrehajtandó művelettel.
type: docs
weight: 1
url: /hu/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) konstruktor


Létrehoz egy [Task](../)-t egy végrehajtandó művelettel.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | A művelet, amelyet aszinkron módon kell végrehajtani |

## Task::Task(const Action<>\&, const CancellationToken\&) konstruktor


Létrehoz egy [Task](../)-t egy művelettel és leállítási tokennel.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | A művelet, amelyet aszinkron módon kell végrehajtani |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Az token a leállítási kérelmek figyelésére |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\>) konstruktor


Létrehoz egy [Task](../)-t állapottal rendelkező művelettel és állapotobjektummal.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | A művelet, amelyet végre kell hajtani (elfogadja az állapotobjektumot) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | A felhasználó által definiált állapotobjektum, amelyet a műveletnek adunk át |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) konstruktor


Létrehoz egy [Task](../)-t állapottal rendelkező művelettel, állapottal és leállítási tokennel.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | A művelet, amelyet végre kell hajtani (elfogadja az állapotobjektumot) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | A felhasználó által definiált állapotobjektum, amelyet a műveletnek adunk át |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Az token a leállítási kérelmek figyelésére |

## Task::Task() konstruktor


Belső konstruktor inicializálatlan feladatok létrehozásához.

```cpp
System::Threading::Tasks::Task::Task()
```

## Lásd még

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)