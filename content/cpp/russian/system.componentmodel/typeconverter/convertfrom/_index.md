---
title: ConvertFrom()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует объекты.
type: docs
weight: 14
url: /ru/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) метод


Преобразует объекты.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |

### Возвращаемое значение

преобразованный объект.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) метод


Преобразует объекты.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |

### Возвращаемое значение

преобразованный объект.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) метод


Преобразует строку в объект.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| value | const [System::String](../../../system/string/)\& | Значение для преобразования. |

### Возвращаемое значение

преобразованный объект.

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeConverter](../)
* Класс [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [String](../../../system/string/)
* Пространство имён [System::ComponentModel](../../)
* Библиотека [Aspose.Slides](../../../)