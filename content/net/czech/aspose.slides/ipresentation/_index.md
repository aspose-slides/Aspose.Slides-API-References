---
title: IPresentation
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Dokument prezentace
type: docs
weight: 6750
url: /cs/aspose.slides/ipresentation/
---
## IPresentation rozhraní

Dokument prezentace

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Vrací všechny vlastní datové části v prezentaci. Pouze pro čtení [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Vrací rozhraní IDisposable. Pouze pro čtení IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Vrací kolekci všech vložených audio souborů v prezentaci. Pouze pro čtení [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Vrací kolekci autorů komentářů. Pouze pro čtení [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datetime. Výchozí čas vytvoření tohoto objektu Presentation. Čtení/zápis DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Vrací vlastní data prezentace. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Vrací výchozí styl textu pro tvary. Pouze pro čtení [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Vrací kolekci podpisů použitých k podepsání prezentace. Pouze pro čtení [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Pouze pro čtení [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Zastupuje číslo prvního snímku v prezentaci. Čtení/zápis Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Vrací správce fontů. Pouze pro čtení [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Vrací správce záhlaví a paty prezentace. Pouze pro čtení [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Poskytuje snadný přístup ke všem hyperodkazům obsaženým ve všech snímcích prezentace (ne v master, rozvržení, poznámkových snímcích). Pouze pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Vrací kolekci všech obrázků v prezentaci. Pouze pro čtení [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Vrací seznam všech snímků rozvržení, které jsou v prezentaci definovány. Pouze pro čtení [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Vrací správce hlavního podkladu výstřižků. Pouze pro čtení [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Vrací správce hlavního podkladu poznámek. Pouze pro čtení [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Vrací seznam všech master snímků definovaných v prezentaci. Pouze pro čtení [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Vrací master téma prezentace. Pouze pro čtení [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Vrací objekt velikosti snímků poznámek. Pouze pro čtení [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Získává správce oprávnění pro tuto prezentaci. Pouze pro čtení [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Vrací seznam všech sekcí snímků definovaných v prezentaci. Pouze pro čtení [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Vrací seznam všech snímků definovaných v prezentaci. Pouze pro čtení [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Vrací objekt velikosti snímku. Pouze pro čtení [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Vrací informace o formátu, ze kterého byla prezentace načtena. Pouze pro čtení [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Získává VBA projekt s makry prezentace. Čtení/zápis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Získává vlastnosti zobrazení celkové prezentace. Pouze pro čtení [`IViewProperties`](../iviewproperties). |

## Metody

| Název | Popis |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Vrací objekty Thumbnail Image pro všechny snímky prezentace. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Vrací objekty Thumbnail Bitmap pro určené snímky prezentace. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s určenou velikostí. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním měřítkem. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Vrací objekty Thumbnail Image pro určené snímky prezentace s určenou velikostí. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastním měřítkem. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Vrací snímek, MasterSlide nebo LayoutSlide podle Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Zvýrazní všechny shody vzorkového textu zadanou barvou. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Zvýrazní všechny shody vzorkového textu zadanou barvou. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Spojí běhy se stejným formátováním ve všech odstavcích ve všech přijatelné tvary na všech snímcích. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Uloží všechny snímky prezentace do sady souborů představujících XAML značkování. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Uloží určené snímky prezentace do proudu ve zvoleném formátu. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu a s dalšími možnostmi. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Uloží určené snímky prezentace do souboru ve zvoleném formátu. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu a s dalšími možnostmi. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do proudu ve zvoleném formátu. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Uloží určené snímky prezentace do souboru ve zvoleném formátu. |

### Viz také

* rozhraní [IPresentationComponent](../ipresentationcomponent)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->