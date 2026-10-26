---
title: set_ReadOnlyRecommended()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la recomendación de solo lectura. Escribe bool.
type: docs
weight: 92
url: /es/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) método


Establece la recomendación de solo lectura. Escribe **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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