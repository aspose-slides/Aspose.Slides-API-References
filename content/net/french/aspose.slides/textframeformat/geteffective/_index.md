---
title: GetEffective
second_title: Référence API Aspose.Slides pour .NET
description: Obtient les données de formatage de cadre de texte effectif avec l'héritage appliqué.
type: docs
weight: 170
url: /fr/aspose.slides/textframeformat/geteffective/
---

## Méthode TextFrameFormat.GetEffective

Obtient les données de formatage de cadre de texte effectif avec l'héritage appliqué.

```csharp
public ITextFrameFormatEffectiveData GetEffective()
```

### Valeur de Retour

Un [`ITextFrameFormatEffectiveData`](../../itextframeformateffectivedata).

### Exemples

Cet exemple démontre l'obtention de certaines propriétés de formatage de cadre de texte effectif.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
    ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.TextFrame.TextFrameFormat.GetEffective();
   
    Console.WriteLine("Type d'ancrage : " + effectiveTextFrameFormat.AnchoringType);
    Console.WriteLine("Type d'ajustement automatique : " + effectiveTextFrameFormat.AutofitType);
    Console.WriteLine("Type de texte vertical : " + effectiveTextFrameFormat.TextVerticalType);
    Console.WriteLine("Marge");
    Console.WriteLine("   Gauche : " + effectiveTextFrameFormat.MarginLeft);
    Console.WriteLine("   Haut : " + effectiveTextFrameFormat.MarginTop);
    Console.WriteLine("   Droite : " + effectiveTextFrameFormat.MarginRight);
    Console.WriteLine("   Bas : " + effectiveTextFrameFormat.MarginBottom);
}
```

### Voir Aussi

* interface [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata)
* class [TextFrameFormat](../../textframeformat)
* namespace [Aspose.Slides](../../textframeformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->