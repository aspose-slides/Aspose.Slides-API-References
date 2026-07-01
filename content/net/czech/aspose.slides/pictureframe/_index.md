---
title: PictureFrame
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje rám s obrázkem uvnitř.
type: docs
weight: 9390
url: /cs/aspose.slides/pictureframe/
---
## PictureFrame class

Reprezentuje rámeček s obrázkem uvnitř.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/Zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojených míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně tvaru. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hyperodkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Určuje, zda je PictureFrame objektem Cameo nebo ne. Pouze pro čtení Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje volbu 'Označit jako dekorativní'. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry tvaru. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. V případě potřeby použijte prázdný řetězec. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Vrací objekt PictureFillFormat pro rámeček s obrázkem. Pouze pro čtení [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací placeholder pro tvar. Vrací null, pokud tvar nemá placeholder. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Vrací nebo nastavuje měřítko výšky (vzhledem k původní velikosti obrázku) rámečku s obrázkem. Hodnota 1,0 odpovídá 100 %. Čtení/Zápis Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Vrací nebo nastavuje měřítko šířky (vzhledem k původní velikosti obrázku) rámečku s obrázkem. Hodnota 1,0 odpovídá 100 %. Čtení/Zápis Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IPictureFrameLock`](../ipictureframelock). (2 vlastnosti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Vrací objekt stylu tvaru. Pouze pro čtení [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Vrací nebo nastavuje typ AutoShape pro PictureFrame. Přípustné jsou všechny položky sady [`ShapeType`](../shapetype), kromě všech druhů čar: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektu pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přemapovat, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru ve z-řadě. Shapes[0] vrací tvar na pozadí z-řady a Shapes[Shapes.Count - 1] vrací tvar v popředí z-řady. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Vytvoří a vrátí pole prvků tvaru. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrátí null, pokud aktuální tvar není zděděn. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí typ ohraničení miniatury je ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Vrací vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrický tvar z objektu [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrický tvar z pole [`IGeometryPath`](../igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Příklady

Následující příklady ukazují, jak změnit miniaturu Audio Frame.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Přidá audio rámec do snímku se zadanou pozicí a velikostí.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Přidá obrázek do zdrojů prezentace.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Nastaví obrázek pro audio rámec.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Uloží upravenou prezentaci na disk
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Viz také

* třída [GeometryShape](../geometryshape)
* rozhraní [IPictureFrame](../ipictureframe)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->