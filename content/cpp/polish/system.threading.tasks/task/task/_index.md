---
title: Task()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy obiekt Task z akcją do wykonania.
type: docs
weight: 1
url: /pl/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) konstruktor

Tworzy [Task](../) z akcją do wykonania.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Akcja do wykonania asynchronicznie |

## Task::Task(const Action<>\&, const CancellationToken\&) konstruktor

Tworzy [Task](../) z akcją i tokenem anulowania.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Akcja do wykonania asynchronicznie |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token do monitorowania żądań anulowania |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) konstruktor

Tworzy [Task](../) z akcją zależną od stanu i obiektem stanu.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Akcja do wykonania (przyjmuje obiekt stanu) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt stanu definiowany przez użytkownika przekazywany do akcji |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) konstruktor

Tworzy [Task](../) z akcją zależną od stanu, stanem i tokenem anulowania.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Akcja do wykonania (przyjmuje obiekt stanu) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt stanu definiowany przez użytkownika przekazywany do akcji |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token do monitorowania żądań anulowania |

## Task::Task() konstruktor

Wewnętrzny konstruktor służący do tworzenia niezainicjowanych zadań.

```cpp
System::Threading::Tasks::Task::Task()
```

## Zobacz również

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Task](../)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)