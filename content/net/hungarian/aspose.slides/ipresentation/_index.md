---
title: IPresentation
second_title: Aspose.Sildes .NET API referencia
description: Prezentáció dokumentum
type: docs
weight: 6770
url: /hu/aspose.slides/ipresentation/
---
## IPresentation interfész

Prezentáció dokumentum

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Visszaadja a prezentáció összes egyéni adat részét. Csak olvasható [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Visszaadja az IDisposable interfészt. Csak olvasható IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Lehetővé teszi az alap IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Visszaadja a prezentációban lévő összes beágyazott hangfájl gyűjteményét. Csak olvasható [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Visszaadja a megjegyzések szerzőinek gyűjteményét. Csak olvasható [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a jelen Presentation objektum létrehozásának időpontja. Olvasás/írás DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Visszaadja a prezentáció egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Visszaadja a prezentáció aláírására használt aláírások gyűjteményét. Csak olvasható [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Visszaadja a DocumentProperties objektumot, amely a standard és egyéni dokumentumtulajdonságokat tartalmazza. Csak olvasható [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | A prezentáció első diájának sorszámát képviseli. Olvasás/írás Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Visszaadja a betűtípuskezelőt. Csak olvasható [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Visszaadja a prezentáció HeaderFooter kezelőjét. Csak olvasható [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Egyszerű hozzáférést biztosít az összes hiperhivatkozáshoz, amelyek minden prezentációs dián találhatók (nem pedig a mester, elrendezés, jegyzet diákban). Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Visszaadja a prezentációban lévő összes kép gyűjteményét. Csak olvasható [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Visszaadja a prezentációban definiált összes elrendezési dia listáját. Csak olvasható [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Visszaadja a szórólap mester kezelőt. Csak olvasható [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Visszaadja a jegyzet mester kezelőt. Csak olvasható [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Visszaadja a prezentációban definiált összes mester dia listáját. Csak olvasható [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Visszaadja a prezentáció mester témáját. Csak olvasható [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Visszaadja a jegyzet dia méret objektumát. Csak olvasható [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Lekéri a prezentáció engedélyek kezelőjét. Csak olvasható [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Visszaadja a prezentációban definiált összes dia szekció listáját. Csak olvasható [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Visszaadja a prezentációban definiált összes dia listáját. Csak olvasható [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Visszaadja a dia méret objektumát. Csak olvasható [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Visszaadja a prezentáció betöltésének formátumára vonatkozó információt. Csak olvasható [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Lekéri a VBA projektet a prezentáció makróival. Olvasás/írás [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Visszaadja a prezentációban lévő összes beágyazott videofájl gyűjteményét. Csak olvasható [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Lekéri a prezentáció széles nézet tulajdonságait. Csak olvasható [`IViewProperties`](../iviewproperties). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Visszaad egy Thumbnail Bitmap objektumot a megadott diákhoz a prezentációban. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Visszaad egy Thumbnail Image objektumot az összes diára a prezentációban a megadott mérettel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Visszaad egy Thumbnail Image objektumot az összes diára a prezentációban egyéni méretezéssel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban a megadott mérettel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban egyéni méretezéssel. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Kiemeli a reguláris kifejezés minden egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Kiemeli a mintaszöveg minden egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Kiemeli a mintaszöveg minden egyezését a megadott színnel. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Összevonja az azonos formázású futamokat az összes bekezdésben, az összes megfelelő alakzatban, az összes dián. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | Újratölti az összes diagram adatát a prezentációban a forrás munkafüzetekből. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Lecseréli a megadott szöveg minden előfordulását egy másik megadott szövegre. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Ment minden diát a prezentációból egy sor fájlba, amely XAML jelölést képvisel. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Ment minden diát a prezentációból egy folyamba a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Ment minden diát a prezentációból egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Ment a megadott diákat a prezentációból egy folyamba a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Ment minden diát a prezentációból egy folyamba a megadott formátumban, további beállításokkal. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Ment a megadott diákat a prezentációból egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Ment minden diát a prezentációból egy fájlba a megadott formátummal és további beállításokkal. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Ment a megadott diákat a prezentációból egy folyamba a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Ment a megadott diákat a prezentációból egy fájlba a megadott formátummal. |

### Lásd még

* interfész [IPresentationComponent](../ipresentationcomponent)
* névtér [Aspose.Slides](../../aspose.slides)
* összeszerelés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->