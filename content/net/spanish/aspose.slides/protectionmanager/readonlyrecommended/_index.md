---
title: ReadOnlyRecommended
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.
type: docs
weight: 60
url: /es/aspose.slides/protectionmanager/readonlyrecommended/
---

## Propiedad ProtectionManager.ReadOnlyRecommended

Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura.

```csharp
public bool ReadOnlyRecommended { get; set; }
```

### Ejemplos

El siguiente código de muestra muestra cómo configurar una presentación de PowerPoint como solo lectura en C# utilizando Aspose.Slides.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	pres.ProtectionManager.ReadOnlyRecommended = true;
	pres.Save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
}
```

### Vea También

* clase [ProtectionManager](../../protectionmanager)
* espacio de nombres [Aspose.Slides](../../protectionmanager)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->