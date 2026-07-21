---
title: ConvertFromString()
second_title: Aspose.Slides для C++: справка по API
description: Преобразует строку в объект.
type: docs
weight: 40
url: /ru/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) метод

Преобразует строку в объект.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Значение для преобразования. |

### Возвращаемое значение

преобразованный объект.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) метод

Преобразует строку в объект.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| text | const [System::String](../../../system/string/)\& | Значение для преобразования. |

### Возвращаемое значение

преобразованный объект.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) метод

Преобразует строку в объект.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| text | const [System::String](../../../system/string/)\& | Значение для преобразования. |

### Возвращаемое значение

преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [String](../../../system/string/)
* Класс [TypeConverter](../)
* Класс [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System::ComponentModel](../../)
* Библиотека [Aspose.Slides](../../../)