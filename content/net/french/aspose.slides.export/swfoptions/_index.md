---
title: SwfOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Fournit des options qui contrôlent comment une présentation est enregistrée au format Swf.
type: docs
weight: 4340
url: /fr/aspose.slides.export/swfoptions/
---

## Classe SwfOptions

Fournit des options qui contrôlent comment une présentation est enregistrée au format Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SwfOptions](swfoptions)() | Constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Spécifie si le document SWF généré doit être compressé ou non. Par défaut, c'est `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retourne ou définit la police utilisée en cas de police source non trouvée. Lecture-écriture String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Active/désactive le menu contextuel. Par défaut, c'est true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retourne ou définit le style visuel du gradient. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Spécifie la qualité des images JPEG. Par défaut, c'est 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être une image PNG de 32x64 pixels, sinon le logo peut être affiché de manière incorrecte. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtient ou définit l'adresse de lien hypertexte complète pour un logo. A un effet uniquement si des [`LogoImageBytes`](./logoimagebytes) sont spécifiés. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression d'enregistrement en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Affiche/masque le panneau inférieur. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Affiche/masque le bouton plein écran. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. Par défaut, c'est `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Affiche/masque le panneau gauche. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Spécifie si la bordure autour des pages doit être affichée. Par défaut, c'est true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Affiche/masque le sélecteur de pages. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Affiche/masque la section de recherche. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Affiche/masque l'ensemble du panneau supérieur. Peut être remplacé dans flashvars. Par défaut, c'est true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture-écriture Boolean. La valeur par défaut est **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). Cette propriété ne prend pas en charge l'affectation d'objets de type [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Commence avec le panneau gauche ouvert. Peut être remplacé dans flashvars. Par défaut, c'est false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure le visualiseur intégré ou non. Par défaut, c'est `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retourne ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture-écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L'exemple suivant montre comment convertir PowerPoint en SWF Flash.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier de présentation
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Enregistrement de la présentation et des pages de notes
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Voir aussi

* class [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->