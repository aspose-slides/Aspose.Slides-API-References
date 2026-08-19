---  
title: IShapeCollection  
second_title: Aspose.Slides voor Java API-referentie  
description: Stelt een collectie van vormen voor.  
type: docs  
url: /nl/com.aspose.slides/ishapecollection/  
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Stelt een verzameling vormen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getParentGroup()](#getParentGroup--) | Haalt het bovenliggende groepsvormobject op voor de vormenverzameling. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt het toe aan het einde van de vormenverzameling. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt het toe aan het einde van de vormenverzameling. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormenverzameling. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en plaatst het in de vormenverzameling op de opgegeven index. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en plaatst het in de vormenverzameling op de opgegeven index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormenverzameling. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormenverzameling. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Maakt een nieuw OLE-objectframe en plaatst het in de vormenverzameling op de opgegeven index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Maakt een nieuw OLE-objectframe en plaatst het in de vormenverzameling op de opgegeven index. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Maakt een nieuw Zoom-frame en plaatst het in de vormenverzameling op de opgegeven index. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en plaatst het in de vormenverzameling op de opgegeven index. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw sectie-Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormenverzameling. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Maakt een nieuw sectie-Zoom-frame en plaatst het in de vormenverzameling op de opgegeven index. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Maakt een nieuw sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en plaatst het in de vormenverzameling op de opgegeven index. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Maakt een nieuw samenvattend Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Maakt een nieuw samenvattend Zoom-frame en plaatst het in de vormenverzameling op de opgegeven index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormenverzameling. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormenverzameling. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Maakt een nieuw video-frame en plaatst het in de vormenverzameling op de opgegeven index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormenverzameling. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en plaatst het in de vormenverzameling op de opgegeven index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormenverzameling. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en plaatst het in de vormenverzameling op de opgegeven index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormenverzameling. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormenverzameling met een bestaande audio-object uit de lijst Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en plaatst het in de vormenverzameling op de opgegeven index. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Maakt een nieuw audio-frame en plaatst het in de vormenverzameling op de opgegeven index met een bestaande audio-object uit de lijst Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Retourneert de nulgebaseerde index van de eerste voorkomens van de opgegeven vorm in de verzameling. |
| [toArray()](#toArray--) | Maakt en retourneert een array die alle vormen bevat. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormenverzameling. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verplaatst de opgegeven vormen binnen de vormenverzameling, en plaatst ze beginnend bij de opgegeven index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de vormenverzameling. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormenverzameling, eventueel initieel met standaard sjabloonopmaak. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Maakt een nieuwe rechthoekige auto-vorm om wiskundige inhoud te bevatten en voegt deze toe aan het einde van de vormenverzameling. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Maakt een nieuwe auto-vorm en plaatst deze in de vormenverzameling op de opgegeven index, met standaard sjabloonopmaak. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Maakt een nieuwe auto-vorm en plaatst deze in de vormenverzameling op de opgegeven index, eventueel initieel met standaard sjabloonstijl. |
| [addGroupShape()](#addGroupShape--) | Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormenverzameling. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Maakt een nieuwe groepsvorm, converteert de opgegeven SVG-afbeelding naar individuele vormen, en voegt de resulterende groep toe aan het einde van de vormenverzameling. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Maakt een nieuwe lege groepsvorm en plaatst deze in de vormenverzameling op de opgegeven index. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Maakt een nieuwe connector-vorm met standaard sjabloonstijl en voegt deze toe aan het einde van de vormenverzameling. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Maakt een nieuwe connector-vorm en voegt deze toe aan het einde van de vormenverzameling, eventueel met standaard sjabloonstijl. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Maakt een nieuwe connector-vorm en plaatst deze in de vormenverzameling op de opgegeven index, met standaard sjabloonstijl. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Maakt een nieuwe connector-vorm en plaatst deze in de vormenverzameling op de opgegeven index, eventueel met standaard sjabloonstijl. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt dit toe aan het einde van de vormenverzameling. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en plaatst dit in de vormenverzameling op de opgegeven index. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormenverzameling. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Maakt een nieuwe tabel en plaatst deze in de vormenverzameling op de opgegeven index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de vorm op de opgegeven index uit de vormenverzameling. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Verwijdert de eerste voorkoming van de opgegeven vorm uit de vormenverzameling. |
| [clear()](#clear--) | Verwijdert alle vormen uit de vormenverzameling. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Maakt een kopie van de opgegeven vorm en plaatst deze in de vormenverzameling op de opgegeven index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Maakt een kopie van de opgegeven vorm en plaatst deze in de vormenverzameling op de opgegeven index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Maakt een kopie van de opgegeven vorm en plaatst deze in de vormenverzameling op de opgegeven index. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Haalt het bovenliggende groepsvormobject op voor de vormenverzameling. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

**Retourwaarde:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt het toe aan het einde van de vormenverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type diagram om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het diagram, in punten. |
| height | float | De hoogte van het diagram, in punten. |

**Retourwaarde:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt het toe aan het einde van de vormenverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type diagram om toe te voegen. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het diagram, in punten. |
| height | float | De hoogte van het diagram, in punten. |
| initWithSample | boolean | True om het nieuwe diagram te initialiseren met voorbeeldserie-gegevens en instellingen; false om het diagram te maken zonder series en slechts minimale instellingen, waardoor creatie sneller gaat. |

**Retourwaarde:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormenverzameling.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het frame van het diagram, in punten. |
| y | float | De y-coördinaat van het frame van het diagram, in punten. |
| width | float | De breedte van het frame van het diagram, in punten. |
| height | float | De hoogte van het frame van het diagram, in punten. |
| layoutType | int | Het SmartArt-lay-outtype. |

**Retourwaarde:**
[ISmartArt](../../com.aspose.slides/ismartart) - Het nieuw aangemaakte [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en plaatst het in de vormenverzameling op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type diagram om te maken. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het nieuwe diagram, in punten. |
| height | float | De hoogte van het nieuwe diagram, in punten. |
| index | int | De nulgebaseerde index waarop het nieuwe diagram moet worden ingevoegd in de vormenverzameling. |

**Retourwaarde:**
[IChart](../../com.aspose.slides/ichart) - Het nieuw aangemaakte [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en plaatst het in de vormenverzameling op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type diagram om te maken. |
| x | float | De x-coördinaat van het nieuwe diagram, in punten. |
| y | float | De y-coördinaat van het nieuwe diagram, in punten. |
| width | float | De breedte van het nieuwe diagram, in punten. |
| height | float | De hoogte van het nieuwe diagram, in punten. |
| index | int | De nulgebaseerde index waarop het nieuwe diagram moet worden ingevoegd in de vormenverzameling. |
| initWithSample | boolean | True om het nieuwe diagram te initialiseren met voorbeeldserie-gegevens en instellingen; false om het diagram te maken zonder series en slechts minimale instellingen, waardoor creatie sneller gaat. |
| initWithSample | boolean | True om de nieuwe chart te initialiseren met voorbeeldreeksgegevens en -instellingen; false om de chart te maken zonder reeksen en alleen minimale instellingen, wat de creatie sneller maakt. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De ingesloten OLE-gegevensinformatie ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klasse-naam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, zal het bestand ontoegankelijk zijn bij het openen van de presentatie vanaf een andere map. |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | De ingesloten OLE-gegevensinformatie ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het OLE-objectframe moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | float | De breedte van het nieuwe OLE-frame, in punten. |
| height | float | De hoogte van het nieuwe OLE-frame, in punten. |
| className | java.lang.String | De klasse-naam van het OLE-object. |
| path | java.lang.String | Het pad naar het gekoppelde bestand.

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, zal het bestand ontoegankelijk zijn bij het openen van de presentatie vanaf een andere map. |

**Retour:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - De nieuw aangemaakte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld laat zien hoe een Zoom-object aan het einde van een collectie wordt toegevoegd
>  (ervan uitgaande dat er minstens twee dia's in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |

**Retour:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld laat zien hoe een Zoom-object aan het einde van een collectie wordt toegevoegd
>  (ervan uitgaande dat er minstens twee dia's in de presentatie "Presentation.pptx" staan):
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst; moet tot deze presentatie behoren. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de gerefereerde dia [IPPImage](../../com.aspose.slides/ippimage). |

**Retour:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Maakt een nieuw Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (ervan uitgaande dat er minstens twee dia's in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst. |

**Retour:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont het maken en invoegen van een Zoom-object op de opgegeven index van een collectie
>  (ervan uitgaande dat er minstens twee dia's in de presentatie "Presentation.pptx" staan):
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [ISlide](../../com.aspose.slides/islide) | De [ISlide](../../com.aspose.slides/islide) waarnaar het Zoom-frame verwijst. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding voor de gerefereerde dia [IPPImage](../../com.aspose.slides/ippimage). |

**Retour:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - De nieuw aangemaakte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Maakt een nieuw Sectie-Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld laat zien hoe een Section Zoom-object aan het einde van een collectie wordt toegevoegd
>  (ervan uitgaande dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Sectie-Zoom-frame verwijst; moet tot deze presentatie behoren en ten minste één dia bevatten. |

**Retour:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld laat zien hoe een Section Zoom-object aan het einde van een collectie wordt toegevoegd
>  (ervan uitgaande dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Sectie-Zoom-frame verwijst; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die moet worden weergegeven binnen het Sectie-Zoom-frame. |

**Retour:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Maakt een nieuw Sectie-Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont de creatie en het invoegen van een Section Zoom-object op de opgegeven index van een collectie
>  (ervan uitgaande dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het Sectie-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Sectie-Zoom-frame verwijst; moet tot deze presentatie behoren en ten minste één dia bevatten. |

**Retour:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont de creatie en het invoegen van een Section Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index beginnend bij nul waarop het Sectie-Zoom-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Sectie-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Sectie-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Sectie-Zoom-frame, in punten. |
| section | [ISection](../../com.aspose.slides/isection) | De [ISection](../../com.aspose.slides/isection) waarnaar het Sectie-Zoom-frame verwijst; moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De afbeelding die moet worden weergegeven binnen het Sectie-Zoom-frame. |

**Retour:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - De nieuw aangemaakte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Maakt een nieuw Samenvatting-Zoom-frame en voegt het toe aan het einde van de vormverzameling.

--------------------

> ```
> Dit voorbeeld laat zien hoe een Summary Zoom-object aan het einde van een collectie wordt toegevoegd
>  (ervan uitgaande dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Samenvatting-Zoom-frame, in punten. |
| width | float | De breedte van het nieuwe Samenvatting-Zoom-frame, in punten. |
| height | float | De hoogte van het nieuwe Samenvatting-Zoom-frame, in punten. |
Deze methode maakt een Summary Zoom frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - De nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Maakt een nieuw Summary Zoom frame en voegt het toe aan de vormverzameling op de opgegeven index.

--------------------

> ```
> Dit voorbeeld toont de creatie en het invoegen van een Summary Zoom-object op de opgegeven index van een collectie
>  (neem aan dat er minstens twee secties in de presentatie "Presentation.pptx" staan):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het Summary Zoom frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| y | float | De y-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| width | float | De breedte van het nieuwe Summary Zoom frame, in punten. |
| height | float | De hoogte van het nieuwe Summary Zoom frame, in punten. |

--------------------

Deze methode maakt een Summary Zoom frame dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert. |

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - De nieuw aangemaakte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - De nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | De [IVideo](../../com.aspose.slides/ivideo) om in het video-frame in te sluiten. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - De nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Maakt een nieuw video-frame en voegt het toe aan de vormverzameling op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het video-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | float | De breedte van het nieuwe video-frame, in punten. |
| height | float | De hoogte van het nieuwe video-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het videobestand om in te sluiten. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - De nieuw aangemaakte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan de vormverzameling op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan de vormverzameling op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| fname | java.lang.String | Het pad of de naam van het externe audiobestand om te koppelen. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het toe aan het einde van de vormverzameling. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiogegevens om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormverzameling met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio)-instantie uit de Presentation.Audios-collectie. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Maakt een nieuw audio-frame met een ingebed WAV-bestand en voegt het toe aan de vormverzameling op de opgegeven index. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio_stream | java.io.InputStream | Een invoerstroom met WAV-audiogegevens om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Maakt een nieuw audio-frame en voegt het toe aan de vormverzameling op de opgegeven index met behulp van een bestaand audio-object uit de Presentation.Audios-lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het audio-frame moet worden ingevoegd. |
| x | float | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | float | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | float | De breedte van het nieuwe audio-frame, in punten. |
| height | float | De hoogte van het nieuwe audio-frame, in punten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Een [IAudio](../../com.aspose.slides/iaudio)-instantie uit de Presentation.Audios-collectie om in te sluiten. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - De nieuw aangemaakte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Retourneert de nul-gebaseerde index van de eerste voorkomens van de opgegeven vorm in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De vorm om in de collectie te lokaliseren. |

**Returns:**
int - De nul-gebaseerde index van de eerste voorkomens van de vorm in de vormverzameling als gevonden; anders, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Maakt een array die alle vormen bevat en retourneert.

**Returns:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape)-objecten.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Maakt een array die alle vormen in het opgegeven bereik bevat en retourneert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | De index van de eerste vorm die moet worden geretourneerd. |
| count | int | Het aantal vormen dat moet worden geretourneerd. |

**Returns:**
com.aspose.slides.IShape[] - Een array van [IShape](../../com.aspose.slides/ishape)-objecten.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde doelindex waar de vorm geplaatst zal worden. |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om binnen de collectie te verplaatsen.

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Verplaatst de opgegeven vormen binnen de vormverzameling, en plaatst ze beginnend op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde doelindex waar de eerste opgegeven vorm zal worden geplaatst; daaropvolgende vormen volgen in de opgegeven volgorde. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Een of meer [IShape](../../com.aspose.slides/ishape)-instanties om binnen de collectie te verplaatsen.

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de auto-vorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het frame van de vorm, in punten. |
| y | float | De y-coördinaat van het frame van de vorm, in punten. |
| width | float | De breedte van het frame van de vorm, in punten. |
| height | float | De hoogte van het frame van de vorm, in punten. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Het nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuwe auto-vorm aan en voegt deze toe aan het einde van de vormcollectie, eventueel initialiserend met de standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de auto-vorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het frame van de vorm, in punten. |
| y | float | De y-coördinaat van het frame van de vorm, in punten. |
| width | float | De breedte van het frame van de vorm, in punten. |
| height | float | De hoogte van het frame van de vorm, in punten. |
| createFromTemplate | boolean | True om de standaard-sjabloonopmaak toe te passen (eenvoudige stijl, gecentreerde tekst en een niet-lege naam) op de nieuwe vorm; false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Het nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Maakt een nieuwe rechthoekige auto-vorm aan om wiskundige inhoud te huisvesten en voegt deze toe aan het einde van de vormcollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het frame van de vorm, in punten. |
| y | float | De y-coördinaat van het frame van de vorm, in punten. |
| width | float | De breedte van het frame van de vorm, in punten. |
| height | float | De hoogte van het frame van de vorm, in punten. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Het nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Maakt een nieuwe auto-vorm aan en voegt deze in de vormcollectie in op de opgegeven index, met standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de nieuwe auto-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de auto-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het frame van de vorm, in punten. |
| y | float | De y-coördinaat van het frame van de vorm, in punten. |
| width | float | De breedte van het frame van de vorm, in punten. |
| height | float | De hoogte van het frame van de vorm, in punten. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Het nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuwe auto-vorm aan en voegt deze in de vormcollectie in op de opgegeven index, eventueel initialiserend met de standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de auto-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de auto-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het frame van de vorm, in punten. |
| y | float | De y-coördinaat van het frame van de vorm, in punten. |
| width | float | De breedte van het frame van de vorm, in punten. |
| height | float | De hoogte van het frame van de vorm, in punten. |
| createFromTemplate | boolean | True om de standaard-sjabloonopmaak toe te passen (inclusief een niet-lege naam, eenvoudige stijl en gecentreerde tekst); false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

**Retour:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Het nieuw aangemaakte [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Maakt een nieuwe lege groepvorm aan en voegt deze toe aan het einde van de vormcollectie. Het frame van de groep past zich automatisch aan om eventuele toegevoegde vormen te bevatten.

**Retour:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Het nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Maakt een nieuwe groepvorm, converteert de opgegeven SVG-afbeelding naar afzonderlijke vormen, en voegt de resulterende groep toe aan het einde van de vormcollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | De [ISvgImage](../../com.aspose.slides/isvgimage) met vectorinhoud die naar vormen moet worden geconverteerd. |
| x | float | De x-coördinaat van het frame van de groep, in punten. |
| y | float | De y-coördinaat van het frame van de groep, in punten. |
| width | float | De breedte van het frame van de groep, in punten. |
| height | float | De hoogte van het frame van de groep, in punten. |

**Retour:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Het nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Maakt een nieuwe lege groepvorm aan en voegt deze in de vormcollectie in op de opgegeven index. Het frame van de groep past zich automatisch aan om eventuele toegevoegde vormen te bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de groepvorm moet worden ingevoegd. |

**Retour:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Het nieuw aangemaakte [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Maakt een nieuwe connector-vorm met standaard-sjabloonopmaak en voegt deze toe aan het einde van de vormcollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden toegevoegd. |
| x | float | De x-coördinaat van het frame van de connector, in punten. |
| y | float | De y-coördinaat van het frame van de connector, in punten. |
| width | float | De breedte van het frame van de connector, in punten. |
| height | float | De hoogte van het frame van de connector, in punten. |

**Retour:**  
[IConnector](../../com.aspose.slides/iconnector) - Het nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuwe connector-vorm en voegt deze toe aan het einde van de vormcollectie, eventueel met standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden aangemaakt. |
| x | float | De x-coördinaat van het frame van de connector, in punten. |
| y | float | De y-coördinaat van het frame van de connector, in punten. |
| width | float | De breedte van het frame van de connector, in punten. |
| height | float | De hoogte van het frame van de connector, in punten. |
| createFromTemplate | boolean | True om de standaard-sjabloonopmaak toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaardeigenschappen. |

**Retour:**  
[IConnector](../../com.aspose.slides/iconnector) - Het nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Maakt een nieuwe connector-vorm en voegt deze in de vormcollectie in op de opgegeven index, met standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de connector-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het frame van de connector, in punten. |
| y | float | De y-coördinaat van het frame van de connector, in punten. |
| width | float | De breedte van het frame van de connector, in punten. |
| height | float | De hoogte van het frame van de connector, in punten. |

**Retour:**  
[IConnector](../../com.aspose.slides/iconnector) - Het nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Maakt een nieuwe connector-vorm en voegt deze in de vormcollectie in op de opgegeven index, eventueel met standaard-sjabloonopmaak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de connector-vorm moet worden ingevoegd. |
| shapeType | int | De [ShapeType](../../com.aspose.slides/shapetype) van de connector-vorm die moet worden ingevoegd. |
| x | float | De x-coördinaat van het frame van de connector, in punten. |
| y | float | De y-coördinaat van het frame van de connector, in punten. |
| width | float | De breedte van het frame van de connector, in punten. |
| height | float | De hoogte van het frame van de connector, in punten. |
| createFromTemplate | boolean | True om de standaard-sjabloonopmaak toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaardeigenschappen. |

**Retour:**  
[IConnector](../../com.aspose.slides/iconnector) - Het nieuw aangemaakte [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Maakt een nieuw picture-frame met de opgegeven afbeelding en voegt dit toe aan het einde van de vormcollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| x | float | De x-coördinaat van het picture-frame, in punten. |
| y | float | De y-coördinaat van het picture-frame, in punten. |
| width | float | De breedte van het picture-frame, in punten. |
| height | float | De hoogte van het picture-frame, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het picture-frame moet worden weergegeven. |

**Retour:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Het nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Maakt een nieuw picture-frame met de opgegeven afbeelding en voegt dit in de vormcollectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het picture-frame moet worden ingevoegd. |
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
| x | float | De x-coördinaat van het picture-frame, in punten. |
| y | float | De y-coördinaat van het picture-frame, in punten. |
| width | float | De breedte van het picture-frame, in punten. |
| height | float | De hoogte van het picture-frame, in punten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | De [IPPImage](../../com.aspose.slides/ippimage) die in het picture-frame moet worden weergegeven. |

**Retour:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Het nieuw aangemaakte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Maakt een nieuwe tabel aan en voegt deze toe aan het einde van de vormcollectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van doubles die de breedtes van de kolommen van de tabel aangeven, in punten. |
| rowHeights | double[] | Een array van doubles die de hoogtes van de rijen van de tabel aangeven, in punten. |

**Retour:**  
[ITable](../../com.aspose.slides/itable) - Het nieuw aangemaakte [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Maakt een nieuwe tabel aan en voegt deze in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de tabel moet worden ingevoegd. |
| x | float | De x-coördinaat van de tabel, in punten. |
| y | float | De y-coördinaat van de tabel, in punten. |
| columnWidths | double[] | Een array van doubles die de breedtes van de kolommen van de tabel vertegenwoordigt, in punten. |
| rowHeights | double[] | Een array van doubles die de hoogtes van de rijen van de tabel vertegenwoordigt, in punten. |

**Retourwaarde:**
[ITable](../../com.aspose.slides/itable) - De nieuw aangemaakte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de vorm op de opgegeven index uit de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen vorm. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Verwijdert de eerste instantie van de opgegeven vorm uit de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te verwijderen. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle vormen uit de vormverzameling.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De vorm om te dupliceren. |
| x | float | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het frame van de gekloonde vorm, in punten. |
| width | float | De breedte van het frame van de gekloonde vorm, in punten. |
| height | float | De hoogte van het frame van de gekloonde vorm, in punten. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De nieuwe vorm behoudt de breedte en hoogte van de sourceShape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te dupliceren. |
| x | float | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het frame van de gekloonde vorm, in punten. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De gekloonde vorm behoudt de positie en grootte van het origineel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te dupliceren. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te dupliceren. |
| x | float | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het frame van de gekloonde vorm, in punten. |
| width | float | De breedte van het frame van de gekloonde vorm, in punten. |
| height | float | De hoogte van het frame van de gekloonde vorm, in punten. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De nieuwe vorm behoudt de breedte en hoogte van de sourceShape.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te dupliceren. |
| x | float | De x-coördinaat van het frame van de gekloonde vorm, in punten. |
| y | float | De y-coördinaat van het frame van de gekloonde vorm, in punten. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De gekloonde vorm behoudt de positie en grootte van het origineel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de gekloonde vorm moet worden ingevoegd. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | De [IShape](../../com.aspose.slides/ishape) om te dupliceren. |

**Retourwaarde:**
[IShape](../../com.aspose.slides/ishape) - De nieuw aangemaakte [IShape](../../com.aspose.slides/ishape).