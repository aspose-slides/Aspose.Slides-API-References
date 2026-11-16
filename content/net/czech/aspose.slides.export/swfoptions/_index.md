---
title: SwfOptions
second_title: Aspose.Sildes pro .NET API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.
type: docs
weight: 4550
url: /cs/aspose.slides.export/swfoptions/
---
## SwfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [SwfOptions](swfoptions)() | Výchozí konstruktor. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Určuje, zda má být vygenerovaný dokument SWF komprimován nebo ne. Výchozí hodnota je `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že není nalezeno výchozí písmo. Čtení-zápis String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Povolit/zakázat kontextové menu. Výchozí hodnota je true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32x64 pixelů, jinak může být logo zobrazeno nesprávně. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Získá nebo nastaví úplnou adresu hypertextového odkazu pro logo. Má efekt pouze, pokud je zadáno [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Zobrazit/skrýt tlačítko na celou obrazovku. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. Výchozí hodnota je `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Určuje, zda má být zobrazen okraj kolem stránek. Výchozí hodnota je true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Zobrazit/skrýt sekci vyhledávání. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace vynechat hypertextové odkazy s voláním JavaScriptu. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). Tato vlastnost nepodporuje přiřazení objektů typu [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Začít s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Určuje, zda má vygenerovaný dokument SWF obsahovat integrovaný prohlížeč dokumentů, nebo ne. Výchozí hodnota je `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Příklady

Následující příklad ukazuje, jak převést PowerPoint do SWF Flash.

```csharp
[C#]
// Vytvoří objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Ukládání prezentace a stránek s poznámkami
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [ISwfOptions](../iswfoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->