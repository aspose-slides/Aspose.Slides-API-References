---
title: Presentation
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje prezentaci Microsoft PowerPoint.
type: docs
weight: 9610
url: /cs/aspose.slides/presentation/
---
## Presentation třída

Represents a Microsoft PowerPoint presentation.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [Presentation](presentation#constructor)() | Tento konstruktor vytváří novou prezentaci od začátku. Vytvořená prezentace má jeden prázdný snímek. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Tento konstruktor vytváří novou prezentaci od začátku. Vytvořená prezentace má jeden prázdný snímek. |
| [Presentation](presentation#constructor_2)(Stream) | Tento konstruktor je hlavním mechanismem pro čtení existující Presentation. |
| [Presentation](presentation#constructor_4)(string) | Tento konstruktor získává cestu k zdrojovému souboru, ze kterého jsou načteny obsah Presentation. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Tento konstruktor je hlavním mechanismem pro čtení existující Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Tento konstruktor získává cestu k zdrojovému souboru, ze kterého jsou načteny obsah Presentation. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Vrací všechny vlastní datové části v prezentaci. Jen pro čtení [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Vrací kolekci všech vložených zvukových souborů v prezentaci. Jen pro čtení [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Vrací kolekci autorů komentářů. Jen pro čtení [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datetime. Ve výchozím nastavení čas vytvoření tohoto objektu Presentation. Čtení/Zápis DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Vrací vlastní data prezentace. Jen pro čtení [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Vrací výchozí styl textu pro tvary. Jen pro čtení [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Vrací kolekci podpisů použité k podepsání prezentace. Jen pro čtení [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Jen pro čtení [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Reprezentuje číslo prvního snímku v prezentaci |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Vrací správce fontů. Jen pro čtení [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Vrací aktuální správce záhlaví a paty. Jen pro čtení [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Poskytuje snadný přístup ke všem hyperodkazům obsaženým ve všech snímcích prezentace (ne v master, layout, notes snímcích). Jen pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Vrací kolekci všech obrázků v prezentaci. Jen pro čtení [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Vrací seznam všech snímků rozvržení definovaných v prezentaci. Jen pro čtení [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Vrací správce ručníku master. Jen pro čtení [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Vrací správce poznámek master. Jen pro čtení [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Vrací seznam všech master snímků definovaných v prezentaci. Jen pro čtení [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Vrací master téma. Jen pro čtení [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Vrací objekt velikosti snímku poznámek. Jen pro čtení [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Získává správce oprávnění pro tuto prezentaci. Jen pro čtení [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Vrací seznam všech sekcí snímků definovaných v prezentaci. Jen pro čtení [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Vrací kolekci štítků citlivosti použitých na dokument prezentace. Jen pro čtení [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Vrací seznam všech snímků definovaných v prezentaci. Jen pro čtení [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Vrací nastavení prezentace (slide show). |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Vrací objekt velikosti snímku. Jen pro čtení [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Vrací informaci o formátu, ze kterého byla prezentace načtena. Jen pro čtení [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Získává nebo nastavuje projekt VBA s makry prezentace. Čtení/Zápis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Vrací kolekci všech vložených video souborů v prezentaci. Jen pro čtení [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Získává obecné vlastnosti zobrazení prezentace. Jen pro čtení [`IViewProperties`](../iviewproperties). |

## Metody

| Název | Popis |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Uvolňuje všechny prostředky používané tímto objektem Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Vrací objekt Image pro všechny snímky prezentace. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Vrací objekt Thumbnail Image pro určené snímky prezentace. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Vrací objekt Thumbnail Image pro všechny snímky prezentace se zadanou velikostí. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Vrací objekt Thumbnail Image pro všechny snímky prezentace se zákaznickým škálováním. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Vrací objekt Thumbnail Image pro určené snímky prezentace se zadanou velikostí. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Vrací objekt Thumbnail Image pro určené snímky prezentace se zákaznickým škálováním. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Spojí běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Uloží všechny snímky prezentace do sady souborů představujících XAML značkování. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Uloží všechny snímky prezentace do souboru se specifikovaným formátem. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dalšími možnostmi. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Uloží určené snímky prezentace do souboru se specifikovaným formátem s zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do souboru se specifikovaným formátem s zachováním číslování stránek. |

### Příklady

Následující příklad ukazuje, jak vytvořit PowerPoint Presentation.

```csharp
[C#]
// Vytvořte objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation())
{
    // Získejte první snímek
    ISlide slide = presentation.Slides[0];
    // Přidejte automatický tvar typu čára
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Uložte soubor prezentace.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Následující příklad ukazuje, jak otevřít a uložit Presentation.

```csharp
[C#]
// Načtěte libovolný podporovaný soubor v Presentation, např. ppt, pptx, odp atd.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Uložte soubor prezentace.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IPresentation](../ipresentation)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->