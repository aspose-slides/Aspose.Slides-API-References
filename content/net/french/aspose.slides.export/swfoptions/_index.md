---
title: SwfOptions
second_title: Référence API Aspose.Slides pour .NET
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
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée en cas de non-fond de police source. Lecture/écriture String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Activer/désactiver le menu contextuel. Par défaut, c'est vrai. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Spécifie la qualité des images JPEG. Par défaut, c'est 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être une image PNG de 32x64 pixels, sinon le logo peut être affiché de manière incorrecte. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtient ou définit l'adresse hypertexte complète pour un logo. N'a d'effet que si un [`LogoImageBytes`](./logoimagebytes) est spécifié. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour mettre à jour les progrès d'enregistrement en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Afficher/masquer le panneau inférieur. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. Par défaut, c'est `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Afficher/masquer le panneau gauche. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Spécifie si une bordure autour des pages doit être affichée. Par défaut, c'est vrai. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Afficher/masquer l'ensemble du panneau supérieur. Peut être remplacé dans les flashvars. Par défaut, c'est vrai. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Booléen. La valeur par défaut est **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). Cette propriété ne prend pas en charge l'attribution d'objets de type [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Commence avec le panneau gauche ouvert. Peut être remplacé dans les flashvars. Par défaut, c'est faux. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure le visualiseur de documents intégré ou non. Par défaut, c'est `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L'exemple suivant montre comment convertir PowerPoint en Flash SWF.

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

* classe [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->