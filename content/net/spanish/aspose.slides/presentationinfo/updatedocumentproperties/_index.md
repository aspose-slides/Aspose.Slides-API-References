---
title: UpdateDocumentProperties
second_title: Referencia de API de Aspose.Slides para .NET
description: Actualiza propiedades de la presentación vinculada.
type: docs
weight: 80
url: /es/aspose.slides/presentationinfo/updatedocumentproperties/
---

## PresentationInfo.UpdateDocumentProperties método

Actualiza propiedades de la presentación vinculada.

```csharp
public void UpdateDocumentProperties(IDocumentProperties documentProperties)
```

### Ejemplos

Este ejemplo muestra cómo llamar al método `UpdateDocumentProperties` para actualizar las propiedades del documento devueltas por la llamada al método [`ReadDocumentProperties`](../readdocumentproperties).

```csharp
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Subject = "Nuevo asunto";
props.LastSavedTime = DateTime.UtcNow;
info.UpdateDocumentProperties(props);
info.WriteBindedPresentation("new_pres.pptx");
```

### Véase También

* interfaz [IDocumentProperties](../../idocumentproperties)
* clase [PresentationInfo](../../presentationinfo)
* espacio de nombres [Aspose.Slides](../../presentationinfo)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->