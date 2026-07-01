---
title: Connector
second_title: Aspose.Sildes pro .NET API Referenci
description: Reprezentuje konektor.
type: docs
weight: 2650
url: /cs/aspose.slides/connector/
---
## Třída Connector

Represents a connector.

```csharp
public class Connector : GeometryShape, IConnector
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Čtení/zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Vrací zámky konektoru. Pouze pro čtení [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vracet null pro některé typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Vrací nebo nastavuje tvar, ke kterému je připojený konec konektoru. Čtení/zápis [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Vrací nebo nastavuje index připojovacího místa pro koncový tvar. Čtení/zápis UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vracet null pro některé typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru v bodech. Čtení/zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hyperodkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje volbu 'Označit jako dekorativní'. Čtení/zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar. Poznámka: může vracet null pro některé typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Pokud je potřeba, použijte prázdný řetězec. Čtení/zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. V opačném případě vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá žádný zástupný prvek. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Čtení/zápis Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IConnectorLock`](../iconnectorlock). (2 vlastnosti) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Vrací objekt stylu tvaru. Pouze pro čtení [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Vrací nebo nastavuje typ AutoShape. Čtení/zápis [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Vrací nebo nastavuje tvar, ke kterému je připojený začátek konektoru. Čtení/zápis [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Vrací nebo nastavuje index připojovacího místa pro počáteční tvar. Čtení/zápis UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektu pro tvar. Poznámka: může vracet null pro některé typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru v bodech. Čtení/zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje x-souřadnici levého horního rohu tvaru v bodech. Čtení/zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje y-souřadnici levého horního rohu tvaru v bodech. Čtení/zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v pořadí z. Shapes[0] vrací tvar na pozadí pořadí z a Shapes[Shapes.Count - 1] vrací tvar v popředí pořadí z. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Vytvoří a vrátí pole elementů tvaru. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrací null, pokud aktuální tvar není zděděn. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou vzhledem k levému hornímu rohu tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Typ hranic miniatury ShapeThumbnailBounds.Shape se používá jako výchozí. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Vrací vizuální hranice tvaru vypočítané z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [Reroute](../../aspose.slides/connector/reroute)() | Přesměruje konektor tak, aby zvolil nejkratší možnou cestu mezi tvary, které spojuje. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](../igeometrypath). Souřadnice musí být vzhledem k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Vlastní. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](../igeometrypath). Souřadnice musí být vzhledem k levému hornímu rohu tvaru. Změní typ tvaru ([`ShapeType`](../geometryshape/shapetype)) na Vlastní. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah Shape jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah Shape jako SVG soubor. |

### Viz také

* třída [GeometryShape](../geometryshape)
* rozhraní [IConnector](../iconnector)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->