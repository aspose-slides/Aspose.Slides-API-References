---
title: get_RefreshThumbnail()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica si la miniatura de la presentación se refrescará. Lectura bool. El valor predeterminado es true.
type: docs
weight: 53
url: /es/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() método


Especifica si la miniatura de la presentación se refrescará. Lectura **bool**. El valor predeterminado es **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* Clase [IPptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)