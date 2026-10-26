---
title: RemoveWriteProtection()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la protección contra escritura de esta presentación.
type: docs
weight: 144
url: /es/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() método


Elimina la protección contra escritura de esta presentación.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Observaciones


Este código de ejemplo muestra cómo eliminar la protección contra escritura de un PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)