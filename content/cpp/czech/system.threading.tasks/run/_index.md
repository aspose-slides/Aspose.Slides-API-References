---
title: Run()
second_title: Aspose.Slides pro C++ API Reference
description: Zařadí specifikovanou práci do fronty ve vláknovém fondu a vrátí úchyt Task pro tuto práci.
type: docs
weight: 157
url: /cs/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) funkce

Zařadí zadanou práci do fronty vlákna a vrátí [Task](../task/) identifikátor pro tuto práci.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Práce, která se má provést asynchronně. |

### Návratová hodnota

[Task](../task/) představuje práci zařazenou do fronty pro provedení ve vláknovém fondu.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) funkce

Zařadí zadanou práci do fronty vlákna a vrátí [Task](../task/) identifikátor pro tuto práci.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Práce, která se má provést asynchronně. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Zrušovací token, který lze použít ke zrušení práce, pokud ještě nezačala. |

### Návratová hodnota

[Task](../task/) představuje práci zařazenou do fronty pro provedení ve vláknovém fondu.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) funkce

Zařadí zadanou práci do fronty vlákna a vrátí proxy pro [Task](../task/) vrácený funkcí.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Práce, která se má provést asynchronně a vrací [Task](../task/). |

### Návratová hodnota

[Task](../task/) představuje proxy pro [Task](../task/) vrácený funkcí.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) funkce

Zařadí zadanou práci do fronty vlákna a vrátí Task<TResult> identifikátor pro tuto práci.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TResult | Typ výsledku vráceného úkolem. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Práce, která se má provést asynchronně. |

### Návratová hodnota

Task<TResult> představuje práci zařazenou do fronty pro provedení ve vláknovém fondu.

## Viz také

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Třída [CancellationToken](../../system.threading/cancellationtoken/)
* Třída [Func](../../system/func/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)