---
title: ISwfOptions
second_title: Aspose.Sildes pour .NET Référence API
description: Fournit des options qui contrôlent comment une présentation est enregistrée au format SWF.
type: docs
weight: 3980
url: /fr/aspose.slides.export/iswfoptions/
---

## Interface ISwfOptions

Fournit des options qui contrôlent comment une présentation est enregistrée au format SWF.

```csharp
public interface ISwfOptions : ISaveOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/iswfoptions/asisaveoptions) { get; } | Renvoie l'interface ISaveOptions. En lecture seule [`ISaveOptions`](../isaveoptions). |
| [Compressed](../../aspose.slides.export/iswfoptions/compressed) { get; set; } | Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est `true`. |
| [EnableContextMenu](../../aspose.slides.export/iswfoptions/enablecontextmenu) { get; set; } | Active/désactive le menu contextuel. La valeur par défaut est vraie. |
| [JpegQuality](../../aspose.slides.export/iswfoptions/jpegquality) { get; set; } | Spécifie la qualité des images JPEG. La valeur par défaut est 95. |
| [LogoImageBytes](../../aspose.slides.export/iswfoptions/logoimagebytes) { get; set; } | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être une image PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte. |
| [LogoLink](../../aspose.slides.export/iswfoptions/logolink) { get; set; } | Obtient ou définit l'adresse hyperlien complète pour un logo. N'a un effet que si un [`LogoImageBytes`](./logoimagebytes) est spécifié. |
| [ShowBottomPane](../../aspose.slides.export/iswfoptions/showbottompane) { get; set; } | Affiche/cache le panneau inférieur. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [ShowFullScreen](../../aspose.slides.export/iswfoptions/showfullscreen) { get; set; } | Affiche/cache le bouton de plein écran. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [ShowHiddenSlides](../../aspose.slides.export/iswfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. La valeur par défaut est `false`. |
| [ShowLeftPane](../../aspose.slides.export/iswfoptions/showleftpane) { get; set; } | Affiche/cache le panneau de gauche. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [ShowPageBorder](../../aspose.slides.export/iswfoptions/showpageborder) { get; set; } | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est vraie. |
| [ShowPageStepper](../../aspose.slides.export/iswfoptions/showpagestepper) { get; set; } | Affiche/cache le sélecteur de page. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [ShowSearch](../../aspose.slides.export/iswfoptions/showsearch) { get; set; } | Affiche/cache la section de recherche. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [ShowTopPane](../../aspose.slides.export/iswfoptions/showtoppane) { get; set; } | Affiche/cache l'ensemble du panneau supérieur. Peut être remplacé dans flashvars. La valeur par défaut est vraie. |
| [SlidesLayoutOptions](../../aspose.slides.export/iswfoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'export d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). Cette propriété ne prend pas en charge l'attribution d'objets de type `Aspose.Slides.Export.HandoutLayoutingOptions` |
| [StartOpenLeftPane](../../aspose.slides.export/iswfoptions/startopenleftpane) { get; set; } | Commence avec le panneau de gauche ouvert. Peut être remplacé dans flashvars. La valeur par défaut est false. |
| [ViewerIncluded](../../aspose.slides.export/iswfoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure le visualiseur de documents intégré ou non. La valeur par défaut est `true`. |

### Voir Aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->