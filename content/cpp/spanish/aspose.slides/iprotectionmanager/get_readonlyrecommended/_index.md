---
title: get_ReadOnlyRecommended()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la recomendación de solo lectura. Lee bool.
type: docs
weight: 79
url: /es/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() método

Obtiene la recomendación de solo lectura. Lee **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [IProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)