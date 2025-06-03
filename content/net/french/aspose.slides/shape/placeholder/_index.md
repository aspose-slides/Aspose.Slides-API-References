---
title: Placeholder
second_title: Référence de l'API Aspose.Slides pour .NET
description: Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule IPlaceholderaspose.slides/iplaceholder.
type: docs
weight: 210
url: /fr/aspose.slides/shape/placeholder/
---

## Propriété Shape.Placeholder

Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule [`IPlaceholder`](../../iplaceholder).

```csharp
public IPlaceholder Placeholder { get; }
```

### Exemples

L'exemple suivant montre comment changer le texte dans l'espace réservé.

```csharp
[C#]
// Instancie une classe Presentation
using (Presentation pres = new Presentation("ReplacingText.pptx"))
{
    // Accède à la première diapositive
    ISlide sld = pres.Slides[0];
    // Itère à travers les formes pour trouver l'espace réservé
    foreach (IShape shp in sld.Shapes)
        if (shp.Placeholder != null)
        {
            // Change le texte dans chaque espace réservé
            ((IAutoShape)shp).TextFrame.Text = "Ceci est un espace réservé";
        }
    // Enregistre la présentation sur le disque
    pres.Save("output_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

L'exemple suivant montre comment définir le texte d'invite dans l'espace réservé.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation2.pptx"))
{
    ISlide slide = pres.Slides[0];
    foreach (IShape shape in slide.Slide.Shapes) // Itère à travers la diapositive
    {
        if (shape.Placeholder != null && shape is AutoShape)
        {
            string text = "";
            if (shape.Placeholder.Type == PlaceholderType.CenteredTitle) // PowerPoint affiche "Cliquez pour ajouter un titre"
            {
                text = "Ajouter un titre";
            }
            else if (shape.Placeholder.Type == PlaceholderType.Subtitle) // Ajoute un sous-titre
            {
                text = "Ajouter un sous-titre";
            }
            ((IAutoShape)shape).TextFrame.Text = text;
            Console.WriteLine($"Espace réservé avec texte : {text}");
        }
    }
    pres.Save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IPlaceholder](../../iplaceholder)
* classe [Shape](../../shape)
* espace de noms [Aspose.Slides](../../shape)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->