---
title: set_ReadOnlyRecommended()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la recomendación de solo lectura. Escribe bool.
type: docs
weight: 92
url: /es/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) método

Establece la recomendación de solo lectura. Escribe **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Observaciones


El siguiente fragmento de código muestra cómo establecer un PowerPoint [Presentation](../../presentation/) como solo lectura en C# usando [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)