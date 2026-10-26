---
title: IShapeCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van vormen voor.
type: docs
url: /nl/com.aspose.slides/ishapecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Stelt een collectie van vormen voor.
## Methodes

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getParentGroup()](#getParentGroup--) | Haalt het bovenliggende groepvormobject op voor de vormencollectie. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het toe aan het einde van de vormencollectie. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het toe aan het einde van de vormencollectie. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Maakt een nieuw SmartArt-diagram en voegt het toe aan het einde van de vormencollectie. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormencollectie. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormencollectie. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en voegt het in op de opgegeven index in de vormencollectie. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en voegt het in op de opgegeven index in de vormencollectie. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw Section-Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormencollectie. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw Section-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Maakt een nieuw Summary-Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Maakt een nieuw Summary-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormencollectie. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in op de opgegeven index in de vormencollectie. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormencollectie. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in op de opgegeven index in de vormencollectie. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormencollectie. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormencollectie met een bestaande audio-object uit de Presentation.Audios-lijst. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het in op de opgegeven index in de vormencollectie. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en voegt het in op de opgegeven index in de vormencollectie met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Retourneert de nulgebaseerde index van de eerste vondst van de opgegeven vorm in de collectie. |
| [toArray()](#toArray--) | Maakt en retourneert een array die alle vormen bevat. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormencollectie. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verplaatst de opgegeven vormen binnen de vormencollectie, startend op de opgegeven index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Maakt een nieuwe autovorm met standaardopmaak en voegt deze toe aan het einde van de vormencollectie. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Maakt een nieuwe autovorm en voegt deze toe aan het einde van de vormencollectie, eventueel initieel met standaard sjabloonopmaak. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Maakt een nieuw rechthoekig autovorm om wiskundige inhoud te huisvesten en voegt deze toe aan het einde van de vormencollectie. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Maakt een nieuwe autovorm en voegt deze in op de opgegeven index in de vormencollectie, met standaard sjabloonopmaak. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Maakt een nieuwe autovorm en voegt deze in op de opgegeven index in de vormencollectie, eventueel initieel met standaard sjabloonstyling. |
| [addGroupShape()](#addGroupShape--) | Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormencollectie. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Maakt een nieuwe groepsvorm, zet de opgegeven SVG-afbeelding om in individuele vormen, en voegt de resulterende groep toe aan het einde van de vormencollectie. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Maakt een nieuwe lege groepsvorm en voegt deze in op de opgegeven index in de vormencollectie. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Maakt een nieuw connector-vorm met standaard sjabloonstyling en voegt deze toe aan het einde van de vormencollectie. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Maakt een nieuw connector-vorm en voegt deze toe aan het einde van de vormencollectie, eventueel met standaard sjabloonstyling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Maakt een nieuw connector-vorm en voegt deze in op de opgegeven index in de vormencollectie, met standaard sjabloonstyling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Maakt een nieuw connector-vorm en voegt deze in op de opgegeven index in de vormencollectie, eventueel met standaard sjabloonstyling. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt deze toe aan het einde van de vormencollectie. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt deze in op de opgegeven index in de vormencollectie. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormencollectie. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Maakt een nieuwe tabel en voegt deze in op de opgegeven index in de vormencollectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de vorm op de opgegeven index uit de vormencollectie. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Verwijdert de eerste vondst van de opgegeven vorm uit de vormencollectie. |
| [clear()](#clear--) | Verwijdert alle vormen uit de vormencollectie. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```


Haalt het element op op de opgegeven index. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```


Haalt het bovenliggende groepvormobject op voor de vormencollectie. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```


Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Het type diagram om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het diagram, in punten. |
| height | float | De hoogte van het diagram, in punten. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```


Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Het type diagram om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het diagram, in punten. |
| height | float | De hoogte van het diagram, in punten. |
| initWithSample | boolean | Waar om het nieuwe diagram te initialiseren met voorbeeldseriedata en instellingen; onwaar om het diagram zonder series en alleen minimale instellingen te maken, waardoor de creatie sneller gaat. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```


Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het diagram-frame, in punten. |
| y | float | De y-coördinaat van het diagram-frame, in punten. |
| width | float | De breedte van het diagram-frame, in punten. |
| height | float | De hoogte van het diagram-frame, in punten. |
| layoutType | int | Het SmartArt-lay-type. |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Het nieuw aangemaakte [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```


Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Het type diagram om te maken. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het nieuwe diagram, in punten. |
| height | float | De hoogte van het nieuwe diagram, in punten. |
| index | int | De nulgebaseerde index waarop het nieuwe diagram in de vormencollectie moet worden ingevoegd. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```


Maakt een nieuw diagram, initialiseert het met voorbeeldseriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Het type diagram om te maken. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het nieuwe diagram, in punten. |
| height | float | De hoogte van het nieuwe diagram, in punten. |
| index | int | De nulgebaseerde index waarop het nieuwe diagram in de vormencollectie moet worden ingevoegd. |
| initWithSample | boolean | Waar om het nieuwe diagram te initialiseren met voorbeeldseriedata en instellingen; onwaar om het diagram zonder series en alleen minimale instellingen te maken, waardoor de creatie sneller gaat. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De ingebedde OLE-datainformatie ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```


Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klassenaam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, is het bestand onbereikbaar bij het openen van de presentatie vanuit een andere map. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```


Maakt een nieuw OLE-objectframe en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De ingebedde OLE-datainformatie ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```


Maakt een nieuw OLE-objectframe en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klassenaam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, is het bestand onbereikbaar bij het openen van de presentatie vanuit een andere map. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Het nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```


Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Zoom-object aan het einde van een collectie
>  (neem aan dat er ten minste twee dia's zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Het nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```


Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Zoom-object aan het einde van een collectie
>  (neem aan dat er ten minste twee dia's zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de verwijzende dia [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Het nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```


Maakt een nieuw Zoom-frame en voegt het in op de opgegeven index in de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het creëren en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er ten minste twee dia's zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Het nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```


Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het creëren en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er ten minste twee dia's zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de verwijzende dia [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Het nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```


Maakt een nieuw Section-Zoom-frame en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Section-Zoom-object aan het einde van een collectie
>  (ga uit van ten minste twee secties in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Section-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Section-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Section-Zoom-frame verwijst; moet tot deze presentatie behoren en minstens één dia bevatten. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Het nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```


Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Section-Zoom-object aan het einde van een collectie
>  (neem aan dat er ten minste twee secties zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Section-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Section-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Section-Zoom-frame verwijst; moet tot deze presentatie behoren en minstens één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die binnen het Section-Zoom-frame wordt weergegeven. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Het nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```


Maakt een nieuw Section-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Section-Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er ten minste twee secties zijn in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het Section-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Section-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Section-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Section-Zoom-frame verwijst; moet tot deze presentatie behoren en minstens één dia bevatten. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Het nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```


Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Section-Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er ten minste twee secties zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het Section-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Section-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Section-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Section-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Section-Zoom-frame verwijst; moet tot deze presentatie behoren en minstens één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding die binnen het Section-Zoom-frame wordt weergegeven. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Het nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```


Maakt een nieuw Summary-Zoom-frame en voegt het toe aan het einde van de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het toevoegen van een Summary-Zoom-object aan het einde van een collectie
>  (neem aan dat er ten minste twee secties zijn in de "Presentation.pptx" presentatie):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Summary-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Summary-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Summary-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Summary-Zoom-frame, in punten.

--------------------

Deze methode maakt een Summary-Zoom-frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Het nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


Maakt een nieuw Summary-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Summary Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er ten minste twee secties zijn in de presentatie "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het Summary-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Summary-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Summary-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Summary-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Summary-Zoom-frame, in punten.

--------------------

Deze methode maakt een Summary-Zoom-frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Het nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | De [IVideo](../../com.aspose.slides/ivideo) om in te sluiten in het video-frame. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


Maakt een nieuw video-frame en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het video-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Het nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormencollectie. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiodata om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormencollectie met een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio)-instantie uit de Presentation.Audios-collectie. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het in op de opgegeven index in de vormencollectie. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiodata om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


Maakt een nieuw audio-frame en voegt het in op de opgegeven index in de vormencollectie met een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio)-instantie uit de Presentation.Audios-collectie om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Het nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


Retourneert de nulgebaseerde index van de eerste vondst van de opgegeven vorm in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De vorm die gezocht moet worden in de collectie. |

**Returns:**
int - De nulgebaseerde index van de eerste vondst van de vorm in de vormencollectie indien gevonden; anders \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


Maakt en retourneert een array die alle vormen bevat.

**Returns:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape)-objecten.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | De index van de eerste vorm die moet worden geretourneerd. |
| count | int | Het aantal vormen dat moet worden geretourneerd. |

**Returns:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape)-objecten.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde doelindex waarop de vorm geplaatst zal worden. |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die verplaatst moet worden binnen de collectie. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


Verplaatst de opgegeven vormen binnen de vormencollectie, startend op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde doelindex waarop de eerste opgegeven vorm geplaatst zal worden; volgende vormen volgen in de opgegeven volgorde. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Een of meer [IShape](../../com.aspose.slides/ishape)-instanties om te verplaatsen binnen de collectie. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


Maakt een nieuwe autovorm met standaardopmaak en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de autovorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het vormframe, in punten. |
| y | float | De y-coördinaat van het vormframe, in punten. |
| width | float | De breedte van het vormframe, in punten. |
| height | float | De hoogte van het vormframe, in punten. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Maakt een nieuwe autovorm en voegt deze toe aan het einde van de vormencollectie, eventueel initieel met standaard sjabloonopmaak.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de autovorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het vormframe, in punten. |
| y | float | De y-coördinaat van het vormframe, in punten. |
| width | float | De breedte van het vormframe, in punten. |
| height | float | De hoogte van het vormframe, in punten. |
| createFromTemplate | boolean | Waar om standaard sjabloonstyling (eenvoudige stijl, gecentreerde tekst en niet-lege naam) toe te passen op de nieuwe vorm; onwaar om de vorm te maken met alle eigenschappen op hun standaardwaarden. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```


Maakt een nieuw rechthoekig autovorm om wiskundige inhoud te huisvesten en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van het vormframe, in punten. |
| y | float | De y-coördinaat van het vormframe, in punten. |
| width | float | De breedte van het vormframe, in punten. |
| height | float | De hoogte van het vormframe, in punten. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```


Maakt een nieuwe autovorm en voegt deze in op de opgegeven index in de vormencollectie, met standaard sjabloonopmaak.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de nieuwe autovorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de autovorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het vormframe, in punten. |
| y | float | De y-coördinaat van het vormframe, in punten. |
| width | float | De breedte van het vormframe, in punten. |
| height | float | De hoogte van het vormframe, in punten. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Maakt een nieuwe autovorm en voegt deze in op de opgegeven index in de vormencollectie, eventueel initieel met standaard sjabloonstyling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de autovorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de autovorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het vormframe, in punten. |
| y | float | De y-coördinaat van het vormframe, in punten. |
| width | float | De breedte van het vormframe, in punten. |
| height | float | De hoogte van het vormframe, in punten. |
| createFromTemplate | boolean | Waar om standaard sjabloonstyling (inclusief niet-lege naam, eenvoudige stijl en gecentreerde tekst) toe te passen; onwaar om de vorm te maken met alle eigenschappen op hun standaardwaarden. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - De nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```


Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormencollectie. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```


Maakt een nieuwe groepsvorm, zet de opgegeven SVG-afbeelding om in individuele vormen, en voegt de resulterende groep toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | De [ISvgImage](../../com.aspose.slides/isvgimage) die vectorinhoud bevat om om te zetten in vormen. |
| x | float | De x-coördinaat van het groepsframe, in punten. |
| y | float | De y-coördinaat van het groepsframe, in punten. |
| width | float | De breedte van het groepsframe, in punten. |
| height | float | De hoogte van het groepsframe, in punten. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```


Maakt een nieuwe lege groepsvorm en voegt deze in op de opgegeven index in de vormencollectie. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de groepsvorm moet worden ingevoegd. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - De nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```


Maakt een nieuwe connector-vorm met standaard sjabloonstyling en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het connector-frame, in punten. |
| y | float | De y-coördinaat van het connector-frame, in punten. |
| width | float | De breedte van het connector-frame, in punten. |
| height | float | De hoogte van het connector-frame, in punten. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Maakt een nieuwe connector-vorm en voegt deze toe aan het einde van de vormencollectie, eventueel met standaard sjabloonstyling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden gemaakt. |
| x | float | De x-coördinaat van het connector-frame, in punten. |
| y | float | De y-coördinaat van het connector-frame, in punten. |
| width | float | De breedte van het connector-frame, in punten. |
| height | float | De hoogte van het connector-frame, in punten. |
| createFromTemplate | boolean | Waar om standaard sjabloonstyling (niet-lege naam, eenvoudige stijl) toe te passen; onwaar om de connector te maken met standaardwaarden. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```


Maakt een nieuwe connector-vorm en voegt deze in op de opgegeven index in de vormencollectie, met standaard sjabloonstyling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de connector-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het connector-frame, in punten. |
| y | float | De y-coördinaat van het connector-frame, in punten. |
| width | float | De breedte van het connector-frame, in punten. |
| height | float | De hoogte van het connector-frame, in punten. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```


Maakt een nieuwe connector-vorm en voegt deze in op de opgegeven index in de vormencollectie, eventueel met standaard sjabloonstyling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de connector-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het connector-frame, in punten. |
| y | float | De y-coördinaat van het connector-frame, in punten. |
| width | float | De breedte van het connector-frame, in punten. |
| height | float | De hoogte van het connector-frame, in punten. |
| createFromTemplate | boolean | Waar om standaard sjabloonstyling (niet-lege naam, eenvoudige stijl) toe te passen; onwaar om de connector te maken met standaardwaarden. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - De nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```


Maakt een nieuw afbeelding-frame dat de opgegeven afbeelding bevat en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Geeft het vormtype aan dat in [ShapeType](../../com.aspose.slides/shapetype) wordt gebruikt, behalve voor alle soorten lijnen:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | De x-coördinaat van het afbeelding-frame, in punten. |
| y | float | De y-coördinaat van het afbeelding-frame, in punten. |
| width | float | De breedte van het afbeelding-frame, in punten. |
| height | float | De hoogte van het afbeelding-frame, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het afbeelding-frame wordt weergegeven. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - De nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```


Maakt een nieuw afbeelding-frame dat de opgegeven afbeelding bevat en voegt dit in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het afbeelding-frame moet worden ingevoegd. |
| shapeType | int | Geeft het vormtype aan dat in [ShapeType](../../com.aspose.slides/shapetype) wordt gebruikt, behalve voor alle soorten lijnen:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | De x-coördinaat van het afbeelding-frame, in punten. |
| y | float | De y-coördinaat van het afbeelding-frame, in punten. |
| width | float | De breedte van het afbeelding-frame, in punten. |
| height | float | De hoogte van het afbeelding-frame, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het afbeelding-frame wordt weergegeven. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - De nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```


Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van double-waarden die de breedtes van de kolommen van de tabel weergeven, in punten. |
| rowHeights | double[] | Een array van double-waarden die de hoogtes van de rijen van de tabel weergeven, in punten. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - De nieuw aangemaakte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```


Maakt een nieuwe tabel en voegt deze in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de tabel moet worden ingevoegd. |
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van double-waarden die de breedtes van de kolommen van de tabel weergeven, in punten. |
| rowHeights | double[] | Een array van double-waarden die de hoogtes van de rijen van de tabel weergeven, in punten. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - De nieuw aangemaakte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert de vorm op de opgegeven index uit de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen vorm. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```


Verwijdert de eerste vondst van de opgegeven vorm uit de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die moet worden verwijderd. |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle vormen uit de vormencollectie.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De vorm die gekloond moet worden. |
| x | float | De x-coördinaat van het gekloonde vormframe, in punten. |
| y | float | De y-coördinaat van het gekloonde vormframe, in punten. |
| width | float | De breedte van het gekloonde vormframe, in punten. |
| height | float | De hoogte van het gekloonde vormframe, in punten. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. De nieuwe vorm behoudt de breedte en hoogte van de bronvorm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |
| x | float | De x-coördinaat van het gekloonde vormframe, in punten. |
| y | float | De y-coördinaat van het gekloonde vormframe, in punten. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. De gekloonde vorm behoudt de oorspronkelijke positie en grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de geklonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |
| x | float | De x-coördinaat van het gekloonde vormframe, in punten. |
| y | float | De y-coördinaat van het gekloonde vormframe, in punten. |
| width | float | De breedte van het gekloonde vormframe, in punten. |
| height | float | De hoogte van het gekloonde vormframe, in punten. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```


Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. De nieuwe vorm behoudt de breedte en hoogte van de bronvorm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de geklonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |
| x | float | De x-coördinaat van het gekloonde vormframe, in punten. |
| y | float | De y-coördinaat van het gekloonde vormframe, in punten. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```


Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. De gekloonde vorm behoudt de oorspronkelijke positie en grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de geklonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) die gekloond moet worden. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).