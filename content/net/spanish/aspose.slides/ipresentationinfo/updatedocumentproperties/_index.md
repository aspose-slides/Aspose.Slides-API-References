---
title: UpdateDocumentProperties
second_title: Referencia de API de Aspose.Slides para .NET
description: Actualiza las propiedades de la presentación vinculada.
type: docs
weight: 80
url: /es/aspose.slides/ipresentationinfo/updatedocumentproperties/
---

## IPresentationInfo.UpdateDocumentProperties método

Actualiza las propiedades de la presentación vinculada.

```csharp
public void UpdateDocumentProperties(IDocumentProperties documentProperties)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentProperties | IDocumentProperties | Propiedades del documento [`IDocumentProperties`](../../idocumentproperties) |

### Ejemplos

Este ejemplo muestra cómo llamar al método `UpdateDocumentProperties` para actualizar las propiedades del documento devueltas por la llamada al método [`ReadDocumentProperties`](../readdocumentproperties).

```csharp
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Subject = "Nuevo tema";
props.LastSavedTime = DateTime.UtcNow;
info.UpdateDocumentProperties(props);
info.WriteBindedPresentation("new_pres.pptx");
```

### Véase También

* interfaz [IDocumentProperties](../../idocumentproperties)
* interfaz [IPresentationInfo](../../ipresentationinfo)
* espacio de nombres [Aspose.Slides](../../ipresentationinfo)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->