---
title: Presentation
second_title: Aspose.Sildes .NET API referencia
description: Microsoft PowerPoint prezentációt képviseli.
type: docs
weight: 9590
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
| [Presentation](presentation#constructor)() | Ez a konstruktor új prezentációt hoz létre teljesen az elejétől. A létrehozott prezentáció egy üres diát tartalmaz. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ez a konstruktor új prezentációt hoz létre teljesen az elejétől. A létrehozott prezentáció egy üres diát tartalmaz. |
| [Presentation](presentation#constructor_2)(Stream) | Ez a konstruktor az elsődleges módja a meglévő Presentation beolvasásának. |
| [Presentation](presentation#constructor_4)(string) | Ez a konstruktor egy forrásfájl elérési útját kapja, ahonnan a Presentation tartalma beolvasásra kerül. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ez a konstruktor az elsődleges módja a meglévő Presentation beolvasásának. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ez a konstruktor egy forrásfájl elérési útját kapja, ahonnan a Presentation tartalma beolvasásra kerül. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Visszaadja a prezentáció összes egyedi adat részét. Csak olvasható [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Visszaadja az összes beágyazott hangfájl gyűjteményét a prezentációban. Csak olvasható [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Visszaadja a megjegyzések szerzőinek gyűjteményét. Csak olvasható [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a dátum- és időmezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. Olvasás/írás DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Visszaadja a prezentáció egyedi adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. Csak olvasható [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Visszaadja a DocumentProperties objektumot, amely standard és egyedi dokumentumtulajdonságokat tartalmaz. Csak olvasható [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | A prezentáció első dia számát képviseli. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Visszaadja a betűkészlet kezelőt. Csak olvasható [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Visszaadja a jelenlegi HeaderFooter kezelőt. Csak olvasható [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián (kivéve mester, elrendezés, jegyzet diasok) található. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Visszaadja a prezentáció összes képét tartalmazó gyűjteményt. Csak olvasható [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Visszaadja a prezentációban definiált összes elrendezési dia listáját. Csak olvasható [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Visszaadja a handout master kezelőt. Csak olvasható [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Visszaadja a notes master kezelőt. Csak olvasható [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Visszaadja a prezentációban definiált összes mester dia listáját. Csak olvasható [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Visszaadja a master témát. Csak olvasható [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Visszaadja a jegyzet dia méret objektumot. Csak olvasható [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Megkapja a prezentáció engedélykezelőjét. Csak olvasható [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Visszaadja a prezentációban definiált összes diarész listaát. Csak olvasható [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Visszaadja a prezentációban definiált összes dia listáját. Csak olvasható [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Visszaadja a prezentáció diavetítés beállításait. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Visszaadja a dia méret objektumot. Csak olvasható [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Visszaadja az információt arról, melyik formátumból lett betöltve a prezentáció. Csak olvasható [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Megkapja vagy beállítja a VBA projektet a prezentáció makróival. Olvasás/írás [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. Csak olvasható [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Megkapja a prezentációra vonatkozó nézet tulajdonságait. Csak olvasható [`IViewProperties`](../iviewproperties). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Felszabadítja a Presentation objektum által használt összes erőforrást. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Visszaad egy Image objektumot a prezentáció minden diájához. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Visszaad egy Thumbnail Image objektumot a prezentáció minden diájához a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Visszaad egy Thumbnail Image objektumot a prezentáció minden diájához egyedi méretezéssel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban a megadott mérettel. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban egyedi méretezéssel. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az Id alapján. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Összevonja a ugyanazon formázású futamokat az összes bekezdésben az összes elfogadható alakzatban és dián. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Elmenti a prezentáció összes diaját XAML jelölőnyelvet reprezentáló fájlok halmazába. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Elmenti a prezentáció összes diaját a megadott formátumban egy streambe. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Elmenti a prezentáció összes diaját a megadott formátummal egy fájlba. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Elmenti a prezentáció meghatározott diáit a megadott formátumban egy streambe, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Elmenti a prezentáció összes diaját a megadott formátumban egy streambe, további beállításokkal. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Elmenti a prezentáció meghatározott diáit a megadott formátummal egy fájlba, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció meghatározott diáit a megadott formátumban egy streambe, megőrizve az oldalszámot. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció meghatározott diáit a megadott formátummal egy fájlba, megőrizve az oldalszámot. |

### Példák

Az alábbi példa bemutatja, hogyan hozhatunk létre PowerPoint Presentation-t.

```csharp
[C#]
// Hozzon létre egy Presentation objektumot, amely egy prezentációfájlt képvisel
using (Presentation presentation = new Presentation())
{
    // Szerezze meg az első diát
    ISlide slide = presentation.Slides[0];
    // Adjon hozzá egy vonal típusú autoshape-et
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Mentse a prezentációfájlt.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Az alábbi példa bemutatja, hogyan nyithatunk meg és menthetünk Presentation-t.

```csharp
[C#]
// Töltsön be bármely támogatott fájlt a Presentation-be, például ppt, pptx, odp stb.
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