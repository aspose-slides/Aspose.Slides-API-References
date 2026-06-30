---
title: Presentation
second_title: Aspose.Sildes a .NET API hivatkozáshoz
description: Microsoft PowerPoint prezentációt képvisel.
type: docs
weight: 9570
url: /hu/aspose.slides/presentation/
---
## Presentation osztály

Microsoft PowerPoint prezentációt képvisel.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [Presentation](presentation#constructor)() | Ez a konstruktor új prezentációt hoz létre az alapoktól. A létrehozott prezentáció egy üres diát tartalmaz. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ez a konstruktor új prezentációt hoz létre az alapoktól. A létrehozott prezentáció egy üres diát tartalmaz. |
| [Presentation](presentation#constructor_2)(Stream) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation](presentation#constructor_4)(string) | Ez a konstruktor egy forrásfájl útvonalát kapja, ahonnan a Presentation tartalma beolvasásra kerül. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ez a konstruktor egy forrásfájl útvonalát kapja, ahonnan a Presentation tartalma beolvasásra kerül. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Visszaadja a prezentáció összes egyéni adat részét. Csak olvasható [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Visszaadja a prezentációban található összes beágyazott audio fájl gyűjteményét. Csak olvasható [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Visszaadja a megjegyzések szerzőinek gyűjteményét. Csak olvasható [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint az aktuális Presentation objektum létrehozásának időpontja. Olvasás/írás DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Visszaadja a prezentáció egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Visszaadja a prezentáció aláírására használt aláírások gyűjteményét. Csak olvasható [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Visszaadja a DocumentProperties objektumot, amely szabványos és egyéni dokumentumtulajdonságokat tartalmaz. Csak olvasható [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | A prezentáció első dia számát képviseli |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Visszaadja a betűtípus-kezelőt. Csak olvasható [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Visszaadja az aktuális FejlécLábléc kezelőt. Csak olvasható [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely a prezentáció összes diájában található (nem a mester, elrendezés, jegyzet diákban). Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Visszaadja a prezentációban lévő összes kép gyűjteményét. Csak olvasható [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Visszaadja a prezentációban definiált összes elrendezés-dia listáját. Csak olvasható [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Visszaadja a kézjegy mesterkezelőt. Csak olvasható [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Visszaadja a jegyzet mesterkezelőt. Csak olvasható [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Visszaadja a prezentációban definiált összes mesterdia listáját. Csak olvasható [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Visszaadja a mester témát. Csak olvasható [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Visszaadja a jegyzet dia méret objektumot. Csak olvasható [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | A prezentáció engedélyeinek kezelőjét adja vissza. Csak olvasható [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Visszaadja a prezentációban definiált összes dia szekció listáját. Csak olvasható [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Visszaadja a prezentációban definiált összes dia listáját. Csak olvasható [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Visszaadja a prezentáció diavetítés beállításait. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Visszaadja a dia méret objektumot. Csak olvasható [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Visszaadja az információt arról, melyik formátumból lett betöltve a prezentáció. Csak olvasható [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Visszaadja vagy beállítja a VBA projektet a prezentáció makrókkal. Olvasás/írás [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. Csak olvasható [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Visszaadja a prezentációra kiterjedő nézeti tulajdonságokat. Csak olvasható [`IViewProperties`](../iviewproperties). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Felszabadítja a Presentation objektum által használt összes erőforrást. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Visszaad egy Image objektumot a prezentáció összes diájához. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához egyedi méretezéssel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban egyedi méretezéssel. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Összevonja az azonos formázású futamokat az összes bekezdésben, minden elfogadható alakzatban minden dián. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Elmenti a prezentáció összes diáját egy XAML jelölést reprezentáló fájlkészletbe. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátumban. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátumban, az oldalszámok megtartásával. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátumban, további beállításokkal. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, az oldalszámok megtartásával. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátumban, az oldalszámok megtartásával. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, az oldalszámok megtartásával. |

### Példák

A következő példa bemutatja, hogyan hozható létre PowerPoint Presentation.

```csharp
[C#]
// Létrehoz egy Presentation objektumot, amely egy prezentáció fájlt képvisel
using (Presentation presentation = new Presentation())
{
    // Az első diát kapja meg
    ISlide slide = presentation.Slides[0];
    // Hozzáad egy vonal típusú automatikus alakzatot
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Elmenti a prezentációfájlt.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

A következő példa bemutatja, hogyan nyitható meg és menthető egy Presentation.

```csharp
[C#]
// Betölti a Presentation bármely támogatott fájlt, pl. ppt, pptx, odp stb.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Elmenti a prezentációfájlt.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Kapcsolódó elemek

* interfész [IPresentation](../ipresentation)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->