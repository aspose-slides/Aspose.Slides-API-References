---
title: Mutex()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт мьютекс без владельца.
type: docs
weight: 1
url: /ru/system.threading/mutex/mutex/
---
## Mutex::Mutex() constructor

Создаёт мьютекс без владельца.

```cpp
System::Threading::Mutex::Mutex()
```

## Mutex::Mutex(bool) constructor

Конструктор.

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initiallyOwned | **bool** | Если true, мьютекс, создаваемый конструктором, будет изначально принадлежать. |

## Mutex::Mutex(bool, const String\&) constructor

Конструктор.

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned, const String &name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initiallyOwned | **bool** | Если true, мьютекс, создаваемый конструктором, будет изначально принадлежать. |
| name | const [String](../../../system/string/)\& | Имя мьютекса. |

## See Also

* Class [Mutex](../)
* Class [String](../../../system/string/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)