---
title: ConvertTo()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja az objektumot a megadott típusra.
type: docs
weight: 27
url: /hu/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) metódus

Átalakítja az objektumot a megadott típusra.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) átalakítási kontextus információja. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Az objektumok átalakításakor használandó kultúra. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) az átalakítandó. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | A céltípus, amelyre konvertálni kell. |

### Visszatérési érték

Átalakított objektum.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [ImageFormatConverter](../)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)