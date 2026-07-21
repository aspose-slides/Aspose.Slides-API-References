---
title: ConvertToString()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует объект в строку.
type: docs
weight: 79
url: /ru/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) method

Преобразует объект в строку.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |

### Возвращаемое значение

Преобразованный объект.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) method

Преобразует объект в строку.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информацию о контексте преобразования. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |

### Возвращаемое значение

Преобразованный объект.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) method

Преобразует объект в строку.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информацию о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культуру, используемую при преобразовании объектов. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |

### Возвращаемое значение

Преобразованный объект.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Object](../../../system/object/)
* Класс [TypeConverter](../)
* Класс [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System::ComponentModel](../../)
* Библиотека [Aspose.Slides](../../../)