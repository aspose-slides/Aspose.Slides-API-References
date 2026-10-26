---
title: ConvertTo()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja az objektumot egy adott típusra.
type: docs
weight: 14
url: /hu/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metódus


Átalakítja az objektumot egy adott típusra.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverziós kontextus információ |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A konvertáláskor használandó kultúra |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Átalakítandó objektum. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | A cél típus, amelyre konvertálni kell. |

### Visszatérési érték

Átalakított objektum.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [ImageConverter](../)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)