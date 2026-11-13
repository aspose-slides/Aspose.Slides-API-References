---
title: Presentation
second_title: Aspose.Sildes .NET API Referencia
description: Microsoft PowerPoint prezentációt képviseli.
type: docs
weight: 9610
url: /hu/aspose.slides/presentation/
---
## Presentation osztály

A Microsoft PowerPoint prezentációt képviseli.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [Presentation](presentation#constructor)() | Ez a konstruktor üres prezentációt hoz létre a semmiből. A létrehozott prezentációnak egy üres diája van. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ez a konstruktor üres prezentációt hoz létre a semmiből. A létrehozott prezentációnak egy üres diája van. |
| [Presentation](presentation#constructor_2)(Stream) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation](presentation#constructor_4)(string) | Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Visszaadja a prezentáció összes egyéni adat részét. Csak olvasható [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Visszaadja a prezentációba beágyazott összes audiofájl gyűjteményét. Csak olvasható [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Visszaadja a megjegyzések szerzőinek gyűjteményét. Csak olvasható [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának ideje. Olvasható/írható DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Visszaadja a prezentáció egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. Csak olvasható [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Visszaadja a DocumentProperties objektumot, amely a szabványos és egyéni dokumentumtulajdonságokat tartalmazza. Csak olvasható [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | A prezentáció első dia számát jelöli |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Visszaadja a betűkészlet kezelőt. Csak olvasható [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Visszaadja a tényleges FejlécLábléc kezelőt. Csak olvasható [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít az összes prezentációs diában (nem a mester, elrendezés, jegyzetdiákban) található hiperhivatkozáshoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Visszaadja a prezentációban található összes kép gyűjteményét. Csak olvasható [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Visszaadja a prezentációban definiált összes elrendezési dia listáját. Csak olvasható [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Visszaadja a kézbesítő mester kezelőt. Csak olvasható [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Visszaadja a jegyzet mester kezelőt. Csak olvasható [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Visszaadja a prezentációban definiált összes mesterdia listáját. Csak olvasható [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Visszaadja a mester témát. Csak olvasható [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Visszaadja a jegyzet dia méret objektumot. Csak olvasható [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Visszaadja a prezentáció engedélykezelőjét. Csak olvasható [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Visszaadja a prezentációban definiált összes dia szakasz listáját. Csak olvasható [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Visszaadja a prezentációban definiált összes dia listáját. Csak olvasható [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Visszaadja a prezentáció diavetítés beállításait. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Visszaadja a dia méret objektumot. Csak olvasható [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Visszaad információt arról, hogy melyik formátumból lett betöltve a prezentáció. Csak olvasható [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. Olvasható/írható [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Visszaadja a prezentációba beágyazott összes videofájl gyűjteményét. Csak olvasható [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Visszaadja a prezentáció teljes körű nézet tulajdonságait. Csak olvasható [`IViewProperties`](../iviewproperties). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Felszabadítja a Presentation objektum által használt összes erőforrást. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Visszaad egy Image objektumot az összes prezentációs diára. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációból. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Visszaad egy Miniatűr Image objektumot az összes prezentációs diára a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Visszaad egy Miniatűr Image objektumot az összes prezentációs diára egyedi méretezéssel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációból a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációból egyedi méretezéssel. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az Id alapján. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Összevonja a ugyanazzal a formázással rendelkező futamokat az összes bekezdésben az összes alkalmas alakzatban az összes dián. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Újratölti az összes diagram adatait a prezentációban a forrás munkafüzetekből. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Elmenti a prezentáció összes diáját egy XAML jelölést reprezentáló fájlok halmazába. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Elmenti a prezentáció összes diáját egy stream-be a megadott formátumban. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy stream-be a megadott formátumban, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Elmenti a prezentáció összes diáját egy stream-be a megadott formátumban, további beállításokkal. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy stream-be a megadott formátumban, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot. |

### Példák

Az alábbi példa bemutatja, hogyan hozhat létre PowerPoint Presentation-t.

```csharp
[C#]
// Hozzon létre egy Presentation objektumot, amely egy prezentációfájlt képvisel
using (Presentation presentation = new Presentation())
{
    // Szerezze meg az első diát
    ISlide slide = presentation.Slides[0];
    // Adjon hozzá egy vonal típusú automatikus alakzatot
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Mentse a prezentációfájlt.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Az alábbi példa bemutatja, hogyan nyithat meg és menthet Presentation-t.

```csharp
[C#]
// Töltsön be bármilyen támogatott fájlt a Presentation-ben, például ppt, pptx, odp stb.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Mentse a prezentációfájlt.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IPresentation](../ipresentation)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->