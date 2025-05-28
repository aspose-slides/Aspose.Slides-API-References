---
title: RemoveWriteProtection
second_title: Aspose.Sildes para referencia de API .NET
description: Elimina la protección contra escritura para esta presentación.
type: docs
weight: 100
url: /es/aspose.slides/protectionmanager/removewriteprotection/
---

## ProtectionManager.RemoveWriteProtection método

Elimina la protección contra escritura para esta presentación.

```csharp
public void RemoveWriteProtection()
```

### Ejemplos

Este código de ejemplo muestra cómo eliminar la protección contra escritura de una presentación de PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.pptx", SaveFormat.Pptx);
}
```

### Ver también

* clase [ProtectionManager](../../protectionmanager)
* espacio de nombres [Aspose.Slides](../../protectionmanager)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->