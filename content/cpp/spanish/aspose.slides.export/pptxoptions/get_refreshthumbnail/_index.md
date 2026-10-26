---
title: get_RefreshThumbnail()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica si la miniatura de la presentación será actualizada. Lectura bool. El valor predeterminado es true.
type: docs
weight: 53
url: /es/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() método


Especifica si la miniatura de la presentación será actualizada. Lectura **bool**. El valor predeterminado es **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Observaciones


Cuando el valor de la opción es **true**, se generará la nueva miniatura.

Cuando el valor de la opción es **false**, la miniatura actual se guardará tal como está.

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