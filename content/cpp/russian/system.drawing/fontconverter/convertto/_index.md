---
title: ConvertTo()
second_title: Aspose.Slides для справки API C++
description: Преобразует объект в конкретный тип.
type: docs
weight: 14
url: /ru/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

Преобразует объект в конкретный тип.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) информация о контексте преобразования. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая при преобразовании объектов. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Объект для преобразования. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Тип, в который нужно преобразовать. |

### Возвращаемое значение

Преобразованный объект.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [FontConverter](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)