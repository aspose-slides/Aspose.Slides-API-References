---
title: ConvertTo()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует объект в конкретный тип.
type: docs
weight: 27
url: /ru/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method

Преобразует объект в конкретный тип.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) для преобразования. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Тип, в который нужно преобразовать. |

### Возвращаемое значение

Преобразованный объект.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [ImageFormatConverter](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)