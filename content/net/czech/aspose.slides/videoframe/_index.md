---
title: VideoFrame
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Reprezentuje video klip na snímku.
type: docs
weight: 11700
url: /cs/aspose.slides/videoframe/
---
## Třída VideoFrame

Represents a video clip on a slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Vrací kolekci hodnot úprav tvaru. Jen pro čtení [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastaví alternativní text přidružený k tvaru. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastaví název alternativního textu přidruženého k tvaru. Čtení/Zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak se tvar zobrazí v režimu černobílého zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Vrací kolekci skrytých titulků přidružených k video rámci. Tato vlastnost je jen pro čtení a vrací [`ICaptionsCollection`](../icaptionscollection) obsahující všechny stopy titulků. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích bodů na tvaru. Jen pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Jen pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti efektu. Jen pro čtení [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Vrací nebo nastaví vložený video objekt. Čtení/Zápis [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti výplně. Jen pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastaví vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Určuje, zda je video zobrazováno v režimu celé obrazovky. Čtení/Zápis Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získá nebo nastaví výšku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Určuje, zda je VideoFrame skrytý. Čtení/Zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastaví hypertextový odkaz definovaný pro kliknutí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Jen pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastaví hypertextový odkaz definovaný pro přejetí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Určuje, zda je PictureFrame objekt typu Cameo. Jen pro čtení Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získá nebo nastaví volbu „Mark as decorative“. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Jen pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Jen pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti čáry. Jen pro čtení [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Vrací nebo nastaví název video souboru, který je propojen s VideoFrame. Čtení/Zápis String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastaví název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Jen pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape, pokud je tvar seskupený. Jinak vrací null. Jen pro čtení [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Vrací objekt PictureFillFormat pro rámec obrázku. Jen pro čtení [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Vrací zámky tvaru. Jen pro čtení [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá zástupný prvek. Jen pro čtení [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Určuje, zda se video opakuje. Čtení/Zápis Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Vrací nebo nastaví režim přehrávání videa. Čtení/Zápis [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Jen pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastaví surové vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Vrací nebo nastaví měřítko výšky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Čtení/Zápis Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Vrací nebo nastaví měřítko šířky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Čtení/Zápis Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Určuje, zda se video automaticky přetočí na začátek, jakmile přehrávání skončí. Čtení/Zápis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastaví počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota označuje otáčení ve směru hodinových ručiček; záporná hodnota otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Vrací zámky tvaru. Jen pro čtení [`IPictureFrameLock`](../ipictureframelock). (2 vlastnosti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Vrací objekt stylu tvaru. Jen pro čtení [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Vrací nebo nastaví typ AutoShape pro PictureFrame. Povoleny jsou všechny položky ze sady [`ShapeType`](../shapetype), kromě všech typů čar: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Jen pro čtení [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti tvaru. Poznámka: může vrátit null u některých typů tvarů, které nemají 3D vlastnosti. Jen pro čtení [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Ořez konce [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Ořez začátku [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro doplňky nebo jiný kód. Protože tuto hodnotu může uživatel nebo program přenastavit, neměla by být využívána jako trvalý jedinečný klíč. Jen pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Vrací nebo nastaví hlasitost zvuku. Čtení/Zápis [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získá nebo nastaví šířku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v pořadí Z. Shapes[0] vrací tvar na pozadí pořadí Z a Shapes[Shapes.Count - 1] vrací tvar v popředí. Jen pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na zadaný. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Vytvoří a vrátí pole prvků tvaru. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní zástupný prvek (prvek z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). Vrátí null, pokud aktuální tvar není odvozen. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí typ je ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [PictureFrame](../pictureframe)
* rozhraní [IVideoFrame](../ivideoframe)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->