---
title: HolderInitializer< T, false >
second_title: Aspose.Slides для C++ справочник API
description: Специализация HolderInitializer для случая, когда T является типом значений. Контекст использования позволяет возвращать ссылку на временные объекты, поскольку гарантировано, что экземпляр будет скопирован вызывающим кодом. Поэтому эта специализация используется только как заглушка и ничего не делает.
type: docs
weight: 1626
url: /ru/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) специализация для случая, когда T является типом значений. Контекст использования позволяет возвращать ссылку на временные объекты, поскольку гарантируется, что экземпляр будет скопирован вызывающим кодом. Таким образом, эта специализация используется только как заглушка и ничего не делает.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Методы

| Метод | Описание |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)