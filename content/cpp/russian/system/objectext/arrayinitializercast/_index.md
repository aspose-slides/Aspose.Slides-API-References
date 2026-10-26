---
title: ArrayInitializerCast()
second_title: Aspose.Slides для справочника API C++
description: Преобразует фундаментальные значения массива (что C# делает неявно, а C++ видимо не делает).
type: docs
weight: 209
url: /ru/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) метод


Преобразует фундаментальные значения массива (что C# делает неявно, а C++ видимо нет).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| To | Целевой тип. |
| From | Исходные типы. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | From ... | Значения для преобразования и помещения в целевой массив. |

### Возвращаемое значение

[Array](../../array/) содержащий преобразованные копии всех аргументов в том же порядке.

## См. также

* Класс [ObjectExt](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)