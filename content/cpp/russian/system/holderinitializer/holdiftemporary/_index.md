---
title: HoldIfTemporary()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает ссылку на rvalue (const)
type: docs
weight: 14
url: /ru/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) метод

Возвращает ссылку на rvalue (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) метод

Возвращает ссылку на rvalue (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) метод

Копирует переданное lvalue в holder, затем возвращает ссылку на holder.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## См. также

* Структура [HolderInitializer](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)