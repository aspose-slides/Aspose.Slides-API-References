---
title: set_RefreshThumbnail()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica si la miniatura de la presentación se actualizará. Escriba bool. El valor predeterminado es true.
type: docs
weight: 66
url: /es/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) método

Especifica si la miniatura de la presentación se actualizará. Escriba **bool**. El valor predeterminado es **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Observaciones

Cuando el valor de la opción es **true**, se generará la nueva miniatura.

Cuando el valor de la opción es **false**, la miniatura actual se guardará tal cual.

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver también

* Clase [PptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)