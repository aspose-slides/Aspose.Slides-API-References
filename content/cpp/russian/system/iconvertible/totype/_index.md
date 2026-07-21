---
title: ToType()
second_title: Aspose.Slides для C++ API Reference
description: "Преобразует значение этого экземпляра в System::Object указанного System::Type, имеющего эквивалентное значение, используя указанные сведения о форматировании, зависящие от культуры."
type: docs
weight: 209
url: /ru/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) метод

Преобразует значение этого экземпляра в [System::Object](../../object/) указанного System::Type, имеющего эквивалентное значение, используя указанные сведения о форматировании, зависящие от культуры.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type, к которому преобразуется значение этого экземпляра. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), предоставляющая сведения о форматировании, зависящие от культуры. |

### Возвращаемое значение

[System::Object](../../object/) экземпляр типа conversionType, значение которого эквивалентно значению этого экземпляра.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Object](../../object/)
* Класс [TypeInfo](../../typeinfo/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [IConvertible](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)