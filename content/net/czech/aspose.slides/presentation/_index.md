---
title: Presentation
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Representuje prezentaci Microsoft PowerPoint.
type: docs
weight: 9590
url: /cs/aspose.slides/presentation/
---
## Třída Presentation

Představuje prezentaci Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [Presentation](presentation#constructor)() | Tento konstruktor vytvoří novou prezentaci od začátku. Vytvořená prezentace má jeden prázdný snímek. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Tento konstruktor vytvoří novou prezentaci od začátku. Vytvořená prezentace má jeden prázdný snímek. |
| [Presentation](presentation#constructor_2)(Stream) | Tento konstruktor je hlavním mechanismem pro načítání existující prezentace. |
| [Presentation](presentation#constructor_4)(string) | Tento konstruktor získává cestu k souboru, ze kterého se načítá obsah prezentace. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Tento konstruktor je hlavním mechanismem pro načítání existující prezentace. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Tento konstruktor získává cestu k souboru, ze kterého se načítá obsah prezentace. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Vrací všechny vlastní datové části v prezentaci. Pouze pro čtení [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Vrací kolekci všech vložených audio souborů v prezentaci. Pouze pro čtení [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Vrací kolekci autorů komentářů. Pouze pro čtení [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datetime. Výchozí hodnota je čas vytvoření tohoto objektu Presentation. Čtení/zápis DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Vrací vlastní data prezentace. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Vrací výchozí styl textu pro tvary. Pouze pro čtení [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Vrací kolekci podpisů používaných k podepsání prezentace. Pouze pro čtení [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Pouze pro čtení [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Reprezentuje číslo prvního snímku v prezentaci |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Vrací správce písem. Pouze pro čtení [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Vrací aktuální správce záhlaví a paty. Pouze pro čtení [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Poskytuje jednoduchý přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v master, rozvržení, poznámkových snímcích). Pouze pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Vrací kolekci všech obrázků v prezentaci. Pouze pro čtení [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Vrací seznam všech snímků rozvržení, které jsou definovány v prezentaci. Pouze pro čtení [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Vrací správce hlavní verze podkladů. Pouze pro čtení [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Vrací správce hlavní verze poznámek. Pouze pro čtení [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Vrací seznam všech hlavních snímků, které jsou v prezentaci definovány. Pouze pro čtení [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Vrací hlavní téma. Pouze pro čtení [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Vrací objekt velikosti snímku poznámek. Pouze pro čtení [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Získá správce oprávnění pro tuto prezentaci. Pouze pro čtení [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Vrací seznam všech sekcí snímků, které jsou v prezentaci definovány. Pouze pro čtení [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Vrací seznam všech snímků, které jsou v prezentaci definovány. Pouze pro čtení [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Vrací nastavení prezentace snímků pro prezentaci. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Vrací objekt velikosti snímku. Pouze pro čtení [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Vrací informace o tom, z jakého formátu byla prezentace načtena. Pouze pro čtení [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Získá nebo nastaví projekt VBA s makry prezentace. Čtení/zápis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Získá vlastnosti zobrazení celého prezentace. Pouze pro čtení [`IViewProperties`](../iviewproperties). |

## Metody

| Název | Popis |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Uvolní všechny prostředky použité tímto objektem Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Vrací objekty Image pro všechny snímky prezentace. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Vrací objekty Thumbnail Image pro určené snímky prezentace. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Vrací objekty Thumbnail Image pro všechny snímky prezentace se zadanou velikostí. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním měřítkem. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Vrací objekty Thumbnail Image pro určené snímky prezentace se zadanou velikostí. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastním měřítkem. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Zvýrazní všechny shody regulárního výrazu zvolenou barvou. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Zvýrazní všechny shody ukázkového textu zvolenou barvou. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Zvýrazní všechny shody ukázkového textu zvolenou barvou. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Spojí běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech na všech snímcích. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Nahradí všechny shody regulárního výrazu zvoleným řetězcem. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Uloží všechny snímky prezentace do sady souborů představujících XAML značkování. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu s dalšími možnostmi. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním číslování stránek. |

### Příklady

Následující příklad ukazuje, jak vytvořit prezentaci PowerPoint.

```csharp
[C#]
// Vytvoří objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation())
{
    // Získá první snímek
    ISlide slide = presentation.Slides[0];
    // Přidá automatický tvar typu čára
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Uloží soubor prezentace.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Následující příklad ukazuje, jak otevřít a uložit prezentaci.

```csharp
[C#]
// Načte jakýkoli podporovaný soubor v Presentation, např. ppt, pptx, odp atd.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Uloží soubor prezentace.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IPresentation](../ipresentation)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->