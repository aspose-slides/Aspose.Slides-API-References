---
title: SwfOptions
second_title: Aspose.Sildes pour .NET Référence de l'API
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.
type: docs
weight: 4530
url: /fr/aspose.slides.export/swfoptions/
---
## Classe SwfOptions

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée si la police source n’est pas trouvée. Chaîne lecture/écriture. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Active ou désactive le menu contextuel. La valeur par défaut est `true`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Spécifie la qualité des images JPEG. La valeur par défaut est 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être un PNG de 32x64 pixels, sinon le logo peut être affiché incorrectement. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Renvoie ou définit l’adresse hypertexte complète d’un logo. N’a d’effet que si un [`LogoImageBytes`](./logoimagebytes) est spécifié. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression d’enregistrement en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Affiche/masque le panneau inférieur. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Affiche/masque le bouton plein écran. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure les diapositives cachées ou non. La valeur par défaut est `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Affiche/masque le panneau gauche. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est `true`. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Affiche/masque le sélecteur de page. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Affiche/masque la section de recherche. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Affiche/masque l’ensemble du panneau supérieur. Peut être substitué dans les flashvars. La valeur par défaut est `true`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s’il faut ignorer les hyperliens contenant des appels JavaScript lors de l’enregistrement de la présentation. Booléen lecture/écriture. La valeur par défaut est **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Renvoie ou définit le mode dans lequel les diapositives sont placées sur la page lors de l’exportation d’une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). Cette propriété ne prend pas en charge l’affectation d’objets du type [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Commencer avec le panneau gauche ouvert. Peut être substitué dans les flashvars. La valeur par défaut est `false`. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure le visualiseur de documents intégré ou non. La valeur par défaut est `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement se poursuit ou doit être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L’exemple suivant montre comment convertir PowerPoint en Flash SWF.

```csharp
[C#]
// Instancie un objet Presentation qui représente un fichier de présentation
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

* classe [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->