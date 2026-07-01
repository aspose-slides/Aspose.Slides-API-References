---
title: AudioFrame
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje audio klip na snímku.
type: docs
weight: 850
url: /cs/aspose.slides/audioframe/
---
## AudioFrame class

Reprezentuje audio klip na snímku.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Properties

| Název | Popis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Vrací kolekci hodnot úprav tvaru. Pouze ke čtení [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Číst/zapisovat String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Číst/zapisovat String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Vrací nebo nastavuje index poslední stopy. Číst/zapisovat Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Vrací nebo nastavuje čas poslední stopy. Číst/zapisovat Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Vrací nebo nastavuje index počáteční stopy. Číst/zapisovat Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Vrací nebo nastavuje čas počáteční stopy. Číst/zapisovat Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Číst/zapisovat [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Získává kolekci uzavřených titulků spojených s audio snímkem. Tato vlastnost je pouze ke čtení a vrací [`ICaptionsCollection`](../icaptionscollection) obsahující všechny stopy titulků. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet míst připojení na tvaru. Pouze ke čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze ke čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty použitých na tvaru. Poznámka: může vrátit null u určitých typů tvarů, které nemají vlastnosti efektu. Pouze ke čtení [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Určuje, zda je zvuk vložen do prezentace. Pouze ke čtení Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Vrací nebo nastavuje vložený audio objekt. Číst/zapisovat [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Určuje časové trvání počátečního fade-in média v milisekundách. Číst/zapisovat Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Určuje časové trvání koncového fade-out média v milisekundách. Číst/zapisovat Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně tvaru. Poznámka: může vrátit null u určitých typů tvarů, které nemají výplňové vlastnosti. Pouze ke čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Číst/zapisovat [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získává nebo nastavuje výšku tvaru, měřenou v bodech. Číst/zapisovat Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skryt. Číst/zapisovat Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Určuje, zda je AudioFrame skryt. Číst/zapisovat Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperlink definovaný pro kliknutí myší. Číst/zapisovat [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hyperlinků. Pouze ke čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperlink definovaný pro najetí myší. Číst/zapisovat [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Určuje, zda je PictureFrame objekt Cameo. Pouze ke čtení Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získává nebo nastavuje volbu „Mark as decorative“. Číst/zapisovat Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze ke čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze ke čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry tvaru. Poznámka: může vrátit null u určitých typů tvarů, které čárové vlastnosti nemají. Pouze ke čtení [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Vrací nebo nastavuje název audio souboru, který je propojen s AudioFrame. Číst/zapisovat String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je to potřeba. Číst/zapisovat String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor platný pro snímek, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze ke čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací null. Pouze ke čtení [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Vrací objekt PictureFillFormat pro picture frame. Pouze ke čtení [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Vrací zámky tvaru. Pouze ke čtení [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací placeholder tvaru. Vrací null, pokud tvar nemá placeholder. Pouze ke čtení [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Určuje, zda se audio přehrává napříč snímky. Číst/zapisovat Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Určuje, zda je audio opakováno. Číst/zapisovat Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Vrací nebo nastavuje režim přehrávání audia. Číst/zapisovat [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze ke čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Číst/zapisovat [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) picture frame. Hodnota 1,0 odpovídá 100 %. Číst/zapisovat Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) picture frame. Hodnota 1,0 odpovídá 100 %. Číst/zapisovat Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Určuje, zda se audio po přehrání automaticky přetočí na začátek. Číst/zapisovat Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je tvar otočen okolo osy Z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Číst/zapisovat Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Vrací zámky tvaru. Pouze ke čtení [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Vrací objekt stylu tvaru. Pouze ke čtení [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Vrací nebo nastavuje typ AutoShape pro PictureFrame. Povolená jsou všechna položky ze sady [`ShapeType`](../shapetype), kromě všech druhů čar: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze ke čtení [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D efekty pro tvar. Poznámka: může vrátit null u určitých typů tvarů, které 3D vlastnosti nemají. Pouze ke čtení [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Určuje časové trvání, které má být odebráno z konce média během přehrávání, v milisekundách. Číst/zapisovat Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Určuje časové trvání, které má být odebráno z začátku média během přehrávání, v milisekundách. Číst/zapisovat Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor platný pro prezentaci, určený pro použití doplňky nebo jiným kódem. Protože může být tento hodnotou přepsána uživatelem nebo programově, neměl by být považován za trvalý jedinečný klíč. Pouze ke čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Vrací nebo nastavuje hlasitost audia. Číst/zapisovat [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Vrací nebo nastavuje hlasitost audia v procentech. Číst/zapisovat Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku tvaru, měřenou v bodech. Číst/zapisovat Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Číst/zapisovat Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Číst/zapisovat Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-pořadí. Shapes[0] vrací tvar na pozadí z-pořadí a Shapes[Shapes.Count - 1] vrací tvar v popředí z-pořadí. Pouze ke čtení Int32. |

## Methods

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud žádný neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Vytvoří a vrátí pole elementů tvaru. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní placeholder tvar (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrací null, pokud aktuální tvar není zděděn. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí se používá typ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah Shape jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah Shape jako SVG soubor. |

### Examples

Následující příklady ukazují, jak změnit možnosti přehrávání audia.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Získá tvar AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Nastaví režim přehrávání na přehrání po kliknutí
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Nastaví hlasitost na nízkou
    audioFrame.Volume = AudioVolumeMode.Low;
    // Nastaví audio tak, aby se přehrávalo napříč snímky
    audioFrame.PlayAcrossSlides = true;
    // Zakáže opakování pro audio
    audioFrame.PlayLoopMode = false;
    // Skryje AudioFrame během prezentace
    audioFrame.HideAtShowing = true;
    // Přetočí audio na začátek po přehrání
    audioFrame.RewindAudio = true;
    // Uloží soubor PowerPoint na disk
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->