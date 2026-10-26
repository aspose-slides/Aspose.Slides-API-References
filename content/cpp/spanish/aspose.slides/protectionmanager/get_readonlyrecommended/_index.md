---
title: get_ReadOnlyRecommended()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la recomendación de solo lectura. Lee bool.
type: docs
weight: 79
url: /es/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() método


Obtiene la recomendación de solo lectura. Lee **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Observaciones


El siguiente código de ejemplo muestra cómo establecer un PowerPoint [Presentation](../../presentation/) como solo lectura en C# usando [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)