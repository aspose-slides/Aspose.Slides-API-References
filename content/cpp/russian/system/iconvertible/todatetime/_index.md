---
title: ToDateTime()
second_title: Aspose.Slides для C++ справочник API
description: "Преобразует значение этого экземпляра в эквивалентный System::DateTime, используя указанную информацию о форматировании, специфичную для культуры."
type: docs
weight: 183
url: /ru/system/iconvertible/todatetime/
---
## IConvertible::ToDateTime(System::SharedPtr\<System::IFormatProvider\>) метод

Преобразует значение этого экземпляра к эквивалентному [System::DateTime](../../datetime/) с использованием указанной информации о форматировании, специфичной для культуры.

```cpp
virtual System::DateTime System::IConvertible::ToDateTime(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), которая предоставляет информацию о форматировании, специфичной для культуры. |

### Возвращаемое значение

Экземпляр [System::DateTime](../../datetime/), эквивалентный значению этого экземпляра.

## См. также

* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [DateTime](../../datetime/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [IConvertible](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)