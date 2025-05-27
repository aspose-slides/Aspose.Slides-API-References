---
title: SetExternalHyperlinkClick
second_title: Referencia API de Aspose.Slides para .NET
description: Establecer un hipervínculo externo al hacer clic.
type: docs
weight: 30
url: /es/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---

## Método HyperlinkManager.SetExternalHyperlinkClick

Establecer un hipervínculo externo al hacer clic.

```csharp
public IHyperlink SetExternalHyperlinkClick(string url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | String | URL del hipervínculo. |

### Ejemplos

El siguiente código de ejemplo muestra cómo agregar un cuadro de texto con hipervínculo.

```csharp
[C#]
// Instancia una clase Presentation que representa un PPTX
using(Presentation pptxPresentation = new Presentation()) {
  // Obtiene la primera diapositiva en la presentación
  ISlide slide = pptxPresentation.Slides[0];
  // Agrega un objeto AutoShape con tipo establecido como Rectángulo
  IShape pptxShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
  // Convierte la forma a AutoShape
  IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
  // Accede a la propiedad ITextFrame asociada con el AutoShape
  pptxAutoShape.AddTextFrame("");
  ITextFrame textFrame = pptxAutoShape.TextFrame;
  // Agrega algo de texto al marco
  textFrame.Paragraphs[0].Portions[0].Text = "Aspose.Slides";
  // Establece el hipervínculo para el texto de la porción
  IHyperlinkManager HypMan = textFrame.Paragraphs[0].Portions[0].PortionFormat.HyperlinkManager;
  HypMan.SetExternalHyperlinkClick("http://www.aspose.com");
  // Guarda la presentación PPTX
  pptxPresentation.Save("hLinkPPTX_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IHyperlink](../../ihyperlink)
* clase [HyperlinkManager](../../hyperlinkmanager)
* espacio de nombres [Aspose.Slides](../../hyperlinkmanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->