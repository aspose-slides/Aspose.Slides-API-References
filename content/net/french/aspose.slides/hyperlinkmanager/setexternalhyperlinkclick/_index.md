---
title: SetExternalHyperlinkClick
second_title: Référence API Aspose.Slides pour .NET
description: Définir un lien hypertexte externe au clic.
type: docs
weight: 30
url: /fr/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---

## HyperlinkManager.SetExternalHyperlinkClick méthode

Définir un lien hypertexte externe au clic.

```csharp
public IHyperlink SetExternalHyperlinkClick(string url)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | String | URL du lien hypertexte. |

### Exemples

Le code d'exemple suivant montre comment ajouter une zone de texte avec un lien hypertexte.

```csharp
[C#]
// Instancie une classe Presentation qui représente un PPTX
using(Presentation pptxPresentation = new Presentation()) {
  // Obtient la première diapositive dans la présentation
  ISlide slide = pptxPresentation.Slides[0];
  // Ajoute un objet AutoShape avec le type défini comme Rectangle
  IShape pptxShape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
  // Cast le shape en AutoShape
  IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
  // Accède à la propriété ITextFrame associée à l'AutoShape
  pptxAutoShape.AddTextFrame("");
  ITextFrame textFrame = pptxAutoShape.TextFrame;
  // Ajoute du texte au cadre
  textFrame.Paragraphs[0].Portions[0].Text = "Aspose.Slides";
  // Définit le lien hypertexte pour le texte de la portion
  IHyperlinkManager HypMan = textFrame.Paragraphs[0].Portions[0].PortionFormat.HyperlinkManager;
  HypMan.SetExternalHyperlinkClick("http://www.aspose.com");
  // Sauvegarde la présentation PPTX
  pptxPresentation.Save("hLinkPPTX_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IHyperlink](../../ihyperlink)
* class [HyperlinkManager](../../hyperlinkmanager)
* namespace [Aspose.Slides](../../hyperlinkmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->