---
title: ToString()
second_title: Aspose.Slides для C++ справка API
description: "Преобразует значение этого экземпляра в эквивалентный System::String, используя указанные сведения о форматировании, специфичные для культуры."
type: docs
weight: 196
url: /ru/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) метод

Преобразует значение этого экземпляра в эквивалентный [System::String](../../string/), используя указанные сведения о форматировании, зависящие от культуры.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) интерфейсная реализация, предоставляющая сведения о форматировании, специфичные для культуры. |

### Возвращаемое значение

[System::String](../../string/) экземпляр, эквивалентный значению этого экземпляра.

## IConvertible::ToString() const метод

Аналог метода C# [Object.ToString()](../../object/tostring/). Позволяет преобразовывать пользовательские объекты в строку.

```cpp
virtual String System::Object::ToString() const
```

### Возвращаемое значение

[String](../../string/) представление, предоставляемое конечным классом.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* класс [String](../../string/)
* класс [IFormatProvider](../../iformatprovider/)
* класс [IConvertible](../)
* пространство имён [System](../../)
* библиотека [Aspose.Slides](../../../)