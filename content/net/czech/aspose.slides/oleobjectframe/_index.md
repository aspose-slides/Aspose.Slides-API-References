---
title: OleObjectFrame
second_title: Aspose.Sildes pro .NET API referenci
description: Reprezentuje OLE objekt na snímku.
type: docs
weight: 9210
url: /cs/aspose.slides/oleobjectframe/
---
## OleObjectFrame třída

Represents an OLE object on a slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem. Čtení/Zápis String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Umožňuje získat základní rozhraní IGraphicalObject. Pouze pro čtení [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslován v černobílém režimu. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet spojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Získává nebo nastavuje informace o vložených OLE datech. Čtení/Zápis [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Vrací název souboru vloženého OLE objektu |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Vrací cestu k vloženému OLE objektu |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámečku tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získává nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získává nebo nastavuje volbu 'Mark as decorative'. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze pro čtení Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Určuje, zda je objekt viditelný jako ikona. Čtení/Zápis Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Určuje, zda je objekt propojen s externím souborem. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Vrací úplnou cestu k propojenému souboru. Bude použito krátké jméno souboru. Pouze pro čtení String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Vrací úplnou cestu k propojenému souboru. Bude použito dlouhé jméno souboru. Čtení/Zápis String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec. Pouze pro čtení String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. V případě potřeby použijte prázdný řetězec. Čtení/Zápis String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Vrací nebo nastavuje název objektu. Čtení/Zápis String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Vrací ProgID objektu. Pouze pro čtení String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt rodičovské GroupShape, pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek (placeholder) pro tvar. Vrací null, pokud tvar nemá žádný placeholder. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací rodičovskou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámečku tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 vlastnosti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací rodičovský snímek tvaru. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Vrací objekt vlastností výplně obrázku OleObject. Pouze pro čtení [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Vrací nebo nastavuje titulek ikony OleObject. Čtení/Zápis String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově přepsána, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. Čtení/Zápis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje x-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje y-souřadnici levého horního rohu tvaru, měřenou v bodech. Čtení/Zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-řazení. Shapes[0] vrací tvar v zadní části z-řazení a Shapes[Shapes.Count - 1] vrací tvar v přední části z-řazení. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar placeholderu (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Pokud aktuální tvar není zděděn, vrátí se null. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí je typ ShapeThumbnailBounds.Shape pro ohraničení miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Nastavuje informace o vložených OLE datech. Tato metoda změní vlastnosti objektu tak, aby odrážely nová data, a nastaví příznak IsObjectLink na false, což indikuje, že OLE objekt je vložený. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako SVG soubor. |

### Příklady

Následující příklad ukazuje, jak přistupovat k OLE objektovým rámcům.

```csharp
[C#]
// Načte soubor PPTX do objektu prezentace
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Přistupuje k prvnímu snímku
    ISlide sld = pres.Slides[0];
    // Přetypuje tvar na OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Načte OLE objekt a zapíše jej na disk
    if (oleObjectFrame != null)
    {
        // Získá data vloženého souboru
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Získá příponu vloženého souboru
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Vytvoří cestu pro uložení extrahovaného souboru
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Uloží extrahovaná data
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Viz také

* třída [GraphicalObject](../graphicalobject)
* rozhraní [IOleObjectFrame](../ioleobjectframe)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->