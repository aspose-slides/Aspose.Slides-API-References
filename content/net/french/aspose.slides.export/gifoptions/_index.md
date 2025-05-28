---
title: GifOptions
second_title: Aspose.Sildes pour .NET Référence API
description: Représente les options d'exportation GIF.
type: docs
weight: 3650
url: /fr/aspose.slides.export/gifoptions/
---

## Classe GifOptions

Représente les options d'exportation GIF.

```csharp
public class GifOptions : SaveOptions, IGifOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GifOptions](gifoptions)() | Initialise une nouvelle instance de la classe GifOptions. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DefaultDelay](../../aspose.slides.export/gifoptions/defaultdelay) { get; set; } | Obtient ou définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si [`AdvanceAfterTime`](../../aspose.slides/islideshowtransition/advanceaftertime) n'est pas définie. La valeur par défaut est 1000. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retourne ou définit la police utilisée en cas de police source non trouvée. Chaîne en lecture-écriture. |
| [ExportHiddenSlides](../../aspose.slides.export/gifoptions/exporthiddenslides) { get; set; } | Détermine si les diapositives cachées seront exportées. La valeur par défaut est false. |
| [FrameSize](../../aspose.slides.export/gifoptions/framesize) { get; set; } | Obtient ou définit la taille de la trame. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retourne ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression des sauvegardes en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie si les hyperliens avec des appels JavaScript doivent être ignorés lors de la sauvegarde de la présentation. Lecture/écriture Boolean. La valeur par défaut est **false**. |
| [TransitionFps](../../aspose.slides.export/gifoptions/transitionfps) { get; set; } | Obtient ou définit le FPS de transition [images/sec] La valeur par défaut est 25. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retourne ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L'exemple suivant montre comment convertir des présentations en GIF animés en utilisant des paramètres personnalisés.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    pres.Save("pres.gif", SaveFormat.Gif, new GifOptions
    {
        FrameSize = new Size(960, 720), // la taille du GIF résultant
        DefaultDelay = 2000, // combien de temps chaque diapositive sera affichée avant de changer pour la suivante
        TransitionFps = 35 // augmenter le FPS pour une meilleure qualité d'animation de transition
    });
}
```

### Voir aussi

* classe [SaveOptions](../saveoptions)
* interface [IGifOptions](../igifoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->