---
title: ConvertTo()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует объект в конкретный тип.
type: docs
weight: 53
url: /ru/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) метод

Преобразует объект в указанный тип.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Тип для преобразования. |

### Возвращаемое значение

Преобразованный объект.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) метод

Преобразует объект в указанный тип.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Тип для преобразования. |

### Возвращаемое значение

Преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [TypeConverter](../)
* Класс [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)