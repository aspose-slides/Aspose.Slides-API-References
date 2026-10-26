---
title: IPresentation
second_title: Aspose.Sildes .NET-hez API hivatkozás
description: Prezentációs dokumentum
type: docs
weight: 6750
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
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Visszaadja a prezentációban beágyazott összes audiofájl gyűjteményét. Csak olvasható [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Visszaadja a megjegyzések szerzőinek gyűjteményét. Csak olvasható [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. Olvasható/írható DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Visszaadja a prezentáció egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Visszaadja a prezentáció aláírására használt aláírások gyűjteményét. Csak olvasható [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Visszaadja a DocumentProperties objektumot, amely szabványos és egyéni dokumentumtulajdonságokat tartalmaz. Csak olvasható [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | A prezentáció első diájának számát képviseli. Olvasható/írható Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Visszaadja a betűtípuskezelőt. Csak olvasható [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Visszaadja a prezentáció HeaderFooter kezelőjét. Csak olvasható [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amelyek az összes prezentációs dián (kivéve a master, layout, notes diák) szerepelnek. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Visszaadja a prezentáció összes képének gyűjteményét. Csak olvasható [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Visszaadja a prezentációban definiált összes elrendezésdia listáját. Csak olvasható [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Visszaadja a handout master kezelőt. Csak olvasható [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Visszaadja a notes master kezelőt. Csak olvasható [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Visszaadja a prezentációban definiált összes master dia listáját. Csak olvasható [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Visszaadja a prezentáció master témáját. Csak olvasható [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Visszaadja a notes dia méretobjektumát. Csak olvasható [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Lekéri a prezentációhoz tartozó jogosultságkezelőt. Csak olvasható [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Visszaadja a prezentációban definiált összes diaszekció listáját. Csak olvasható [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Visszaadja a prezentációban definiált összes dia listáját. Csak olvasható [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Visszaadja a dia méretobjektumát. Csak olvasható [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Visszaadja az információt arról, hogy melyik formátumból lett betöltve a prezentáció. Csak olvasható [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Lekéri a VBA projektet a prezentáció makróival. Olvasható/írható [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Visszaadja a prezentációban beágyazott összes videofájl gyűjteményét. Csak olvasható [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Lekéri a prezentációra kiterjedő nézeti tulajdonságokat. Csak olvasható [`IViewProperties`](../iviewproperties). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Visszaad egy vagy több miniatűr kép objektumot a prezentáció minden diájához. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Visszaad egy vagy több miniatűr bitmap objektumot a prezentáció meghatározott diáihoz. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Visszaad egy vagy több miniatűr kép objektumot a prezentáció minden diájához a megadott mérettel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Visszaad egy vagy több miniatűr kép objektumot a prezentáció minden diájához egyedi méretezéssel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Visszaad egy vagy több miniatűr kép objektumot a prezentáció meghatározott diáihoz a megadott mérettel. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Visszaad egy vagy több miniatűr kép objektumot a prezentáció meghatározott diáihoz egyedi méretezéssel. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az azonosító alapján. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Összevonja ugyanazt a formázást tartalmazó futamokat az összes bekezdésben, minden megfelelő alakzatban, minden diában. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | A reguláris kifejezés összes egyezését a megadott szöveggel helyettesíti. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | A megadott szöveg összes előfordulását egy másik megadott szöveggel helyettesíti. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Elmenti a prezentáció összes diáját egy sor fájlba, amelyek XAML jelölést képviselnek. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Elmenti a prezentáció összes diáját egy streambe a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy streambe a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Elmenti a prezentáció összes diáját egy streambe a megadott formátumban, plusz további beállításokkal. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal és további beállításokkal. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy streambe a megadott formátumban. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal. |

### Lásd még

* interfész [IPresentationComponent](../ipresentationcomponent)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->