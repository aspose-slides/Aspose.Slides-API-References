---
title: IShapeCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av former.
type: docs
url: /sv/com.aspose.slides/ishapecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Representerar en samling former.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getParentGroup()](#getParentGroup--) | Hämtar gruppformens föräldraobjekt för samlingen av former. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objekt-ram och lägger till den i slutet av formsamlingen. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Skapar en ny OLE-objekt-ram och infogar den i formsamlingen på det angivna indexet. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny sektions-Zoom-ram och lägger till den i slutet av formsamlingen. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny sektions-Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Skapar en ny sektions-Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Skapar en ny sektions-Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Skapar en ny sammanfattnings-Zoom-ram och lägger till den i slutet av formsamlingen. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Skapar en ny sammanfattnings-Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Skapar en ny ljud-ram länkad till ett CD-spår och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Skapar en ny ljud-ram länkad till ett CD-spår och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Skapar en ny ljud-ram länkad till en extern ljudfil och lägger till den i slutet av formsamlingen. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Skapar en ny ljud-ram länkad till en extern ljudfil och infogar den i formsamlingen på det angivna indexet. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Skapar en ny ljud-ram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljud-ram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Skapar en ny ljud-ram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Skapar en ny ljud-ram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [toArray()](#toArray--) | Skapar och returnerar en array som innehåller alla former. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Flyttar den angivna formen till en ny position inom formsamlingen. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Flyttar de angivna formerna inom formsamlingen och placerar dem med start på det angivna indexet. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Skapar en ny autoform med standardformatering och lägger till den i slutet av formsamlingen. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Skapar en ny autoform och lägger till den i slutet av formsamlingen, valfritt initierad med standardmallens formatering. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Skapar en ny rektangulär autoform för att innehålla matematiskt innehåll och lägger till den i slutet av formsamlingen. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Skapar en ny autoform och infogar den i formsamlingen på det angivna indexet, med standardmallens formatering. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Skapar en ny autoform och infogar den i formsamlingen på det angivna indexet, valfritt initierad med standardmallens stil. |
| [addGroupShape()](#addGroupShape--) | Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former, och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Skapar en ny tom gruppform och infogar den i formsamlingen på det angivna indexet. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Skapar en ny anslutningsform med standardmallens stil och lägger till den i slutet av formsamlingen. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, valfritt tillämpande standardmallens stil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, med standardmallens stil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, valfritt med standardmallens stil. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Skapar en ny bildram som innehåller den angivna bilden och infogar den i formsamlingen på det angivna indexet. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort formen på det angivna indexet från formsamlingen. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [clear()](#clear--) | Tar bort alla former från formsamlingen. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Hämtar elementet på det angivna indexet. Endast läsning [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnvärde:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Hämtar gruppformens föräldraobjekt för samlingen av former. Endast läsning [IGroupShape](../../com.aspose.slides/igroupshape).

**Returnvärde:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtyp att lägga till. |
| x | float | x-koordinaten för det nya diagrammet, i punkter. |
| y | float | y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |

**Returnvärde:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtyp att lägga till. |
| x | float | x-koordinaten för det nya diagrammet, i punkter. |
| y | float | y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |
| initWithSample | boolean | Sant för att initiera det nya diagrammet med exempelseriedata och inställningar; falskt för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |

**Returnvärde:**
[IChart](../../com.aspose.slides/ichart) - Den nyss skapade [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för diagrammets ram, i punkter. |
| y | float | y-koordinaten för diagrammets ram, i punkter. |
| width | float | Bredden på diagrammets ram, i punkter. |
| height | float | Höjden på diagrammets ram, i punkter. |
| layoutType | int | SmartArt-layouttypen. |

**Returnvärde:**
[ISmartArt](../../com.aspose.slides/ismartart) - Den nyss skapade [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtyp att skapa. |
| x | float | x-koordinaten för det nya diagrammet, i punkter. |
| y | float | y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |
| index | int | Det nollbaserade indexet där det nya diagrammet ska infogas i formsamlingen. |

**Returnvärde:**
[IChart](../../com.aspose.slides/ichart) - Det nyss skapade [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och infogar det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Diagramtyp att skapa. |
| x | float | x-koordinaten för det nya diagrammet, i punkter. |
| y | float | y-koordinaten för det nya diagrammet, i punkter. |
| width | float | Bredden på det nya diagrammet, i punkter. |
| height | float | Höjden på det nya diagrammet, i punkter. |
| index | int | Det nollbaserade indexet där det nya diagrammet ska infogas i formsamlingen. |
| initWithSample | boolean | Sant för att initiera det nya diagrammet med exempelseriedata och inställningar; falskt för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |
| initWithSample | boolean | Sant för att initiera det nya diagrammet med exempelseriedata och inställningar; falskt för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet snabbare. |

**Returnerar:**  
[IChart](../../com.aspose.slides/ichart) - Det nysskapade [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar ett nytt OLE-objektram och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för det nya OLE-ramen, i punkter. |
| width | float | Bredden på det nya OLE-ramen, i punkter. |
| height | float | Höjden på det nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}  
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Skapar ett nytt OLE-objektram och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för det nya OLE-ramen, i punkter. |
| width | float | Bredden på det nya OLE-ramen, i punkter. |
| height | float | Höjden på det nya OLE-ramen, i punkter. |
| className | java.lang.String | Klassnamnet för OLE-objektet. |
| path | java.lang.String | Sökvägen till den länkade filen.  

Den här sökvägen lagras exakt som den är i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Skapar ett nytt OLE-objektram och sätter in det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där OLE-objektramen ska infogas. |
| x | float | X-koordinaten för det nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för det nya OLE-ramen, i punkter. |
| width | float | Bredden på det nya OLE-ramen, i punkter. |
| height | float | Höjden på det nya OLE-ramen, i punkter. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returnerar:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}  
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Skapar ett nytt OLE-objektram och sätter in det i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där OLE-objektramen ska infogas. |
| x | float | X-koordinaten för det nya OLE-ramen, i punkter. |
| y | float | Y-koordinaten för det nya OLE-ramen, i punkter. |
| width | float | Bredden på det nya OLE-ramen, i punkter. |
| height | float | Höjden på det nya OLE-ramen, i punkter. |
| className | java.lang.String | Klassnamnet för OLE-objektet. |
| path | java.lang.String | Sökvägen till den länkade filen.  

Den här sökvägen lagras exakt som den är i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog. |

**Returnerar:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Det nysskapade [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}  
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Skapar ett nytt Zoom-ram och lägger till det i slutet av formsamlingen.

--------------------

> ```
> Det här exemplet visar hur man lägger till ett Zoom-objekt i slutet av en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | Den [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till; måste tillhöra denna presentation. |

**Returnerar:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar ett nytt Zoom-ram och lägger till det i slutet av formsamlingen.

--------------------

> ```
> Detta exempel visar hur man lägger till ett Zoom-objekt i slutet av en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | Den [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till; måste tillhöra denna presentation. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden för den refererade sliden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}  
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Skapar ett nytt Zoom-ram och sätter in det i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där Zoom-ramen ska infogas. |
| x | float | X-koordinaten för det nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | Den [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till. |

**Returnerar:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Skapar ett nytt Zoom-ram med en fördefinierad bild och sätter in det i formsamlingen på det angivna indexet.

--------------------

> ```
> Detta exempel visar hur man skapar och infogar ett Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två bilder i presentationen "Presentation.pptx"):
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där Zoom-ramen ska infogas. |
| x | float | X-koordinaten för det nya Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Zoom-ramen, i punkter. |
| slide | [ISlide](../../com.aspose.slides/islide) | Den [ISlide](../../com.aspose.slides/islide) som Zoom-ramen refererar till. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden för den refererade sliden [IPPImage](../../com.aspose.slides/ippimage). |

**Returnerar:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Det nysskapade [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}  
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Skapar ett nytt Section-Zoom-ram och lägger till det i slutet av formsamlingen.

--------------------

> ```
> Detta exempel visar hur man lägger till ett Section Zoom-objekt i slutet av en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | Den [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra denna presentation och innehålla minst en slide. |

**Returnerar:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar ett nytt Section-Zoom-ram med en fördefinierad bild och lägger till det i slutet av formsamlingen.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | Den [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra denna presentation och innehålla minst en slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i Section-Zoom-ramen. |

**Returnerar:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}  
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Skapar ett nytt Section-Zoom-ram och sätter in det i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar hur man skapar och inför ett Section Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där Section-Zoom-ramen ska infogas. |
| x | float | X-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | Den [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra denna presentation och innehålla minst en slide. |

**Returnerar:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Skapar ett nytt Section-Zoom-ram med en fördefinierad bild och sätter in det i formsamlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar skapandet och infogandet av ett Section Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index där Section-Zoom-ramen ska infogas. |
| x | float | X-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Section-Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Section-Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Section-Zoom-ramen, i punkter. |
| section | [ISection](../../com.aspose.slides/isection) | Den [ISection](../../com.aspose.slides/isection) som Section-Zoom-ramen refererar till; måste tillhöra denna presentation och innehålla minst en slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bilden som ska visas i Section-Zoom-ramen. |

**Returnerar:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Det nysskapade [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}  
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Skapar ett nytt Summary-Zoom-ram och lägger till det i slutet av formsamlingen.

--------------------

> ```
> Detta exempel visar hur man lägger till ett Summary Zoom-objekt i slutet av en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för det nya Summary-Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för det nya Summary-Zoom-ramen, i punkter. |
| width | float | Bredden på det nya Summary-Zoom-ramen, i punkter. |
| height | float | Höjden på det nya Summary-Zoom-ramen, i punkter. |
Denna metod skapar en Summary Zoom-ram som samlar sammanfattningslänkar för alla avsnitt i presentationen. |

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Det nyss skapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Skapar en ny Summary Zoom-ram och infogar den i shape-samlingen på det angivna indexet.

--------------------

> ```
> Det här exemplet visar skapande och infogning av ett Summary Zoom-objekt på det angivna indexet i en samling
>  (anta att det finns minst två sektioner i presentationen "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Summary Zoom-ramen ska infogas. |
| x | float | X-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | float | Y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | float | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | float | Höjden på den nya Summary Zoom-ramen, i punkter. |

--------------------

Denna metod skapar en Summary Zoom-ram som samlar sammanfattningslänkar för alla avsnitt i presentationen. |

**Returnerar:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Det nyss skapade [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Skapar en ny video-ram och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Det nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Skapar en ny video-ram och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) att bädda in i video-ramen. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Det nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny video-ram och infogar den i shape-samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där video-ramen ska infogas. |
| x | float | X-koordinaten för den nya video-ramen, i punkter. |
| y | float | Y-koordinaten för den nya video-ramen, i punkter. |
| width | float | Bredden på den nya video-ramen, i punkter. |
| height | float | Höjden på den nya video-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på videofilen som ska bäddas in. |

**Returnerar:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Det nyss skapade [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Skapar en ny audio-ram kopplad till ett CD-spår och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Skapar en ny audio-ram kopplad till ett CD-spår och infogar den i shape-samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där audio-ramen ska infogas. |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Skapar en ny audio-ram kopplad till en extern ljudfil och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Skapar en ny audio-ram kopplad till en extern ljudfil och infogar den i shape-samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där audio-ramen ska infogas. |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| fname | java.lang.String | Sökvägen eller namnet på den externa ljudfilen som ska länkas. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny audio-ram med en inbäddad WAV-fil och lägger till den i slutet av shape-samlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| audio_stream | java.io.InputStream | En input-ström som innehåller WAV-ljuddata att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Skapar en ny audio-ram och lägger till den i slutet av shape-samlingen med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | En [IAudio](../../com.aspose.slides/iaudio)-instans från Presentation.Audios-samlingen. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Skapar en ny audio-ram med en inbäddad WAV-fil och infogar den i shape-samlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där audio-ramen ska infogas. |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| audio_stream | java.io.InputStream | En input-ström som innehåller WAV-ljuddata att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Skapar en ny audio-ram och infogar den i shape-samlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där audio-ramen ska infogas. |
| x | float | X-koordinaten för den nya audio-ramen, i punkter. |
| y | float | Y-koordinaten för den nya audio-ramen, i punkter. |
| width | float | Bredden på den nya audio-ramen, i punkter. |
| height | float | Höjden på den nya audio-ramen, i punkter. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | En [IAudio](../../com.aspose.slides/iaudio)-instans från Presentation.Audios-samlingen att bädda in. |

**Returnerar:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Det nyss skapade [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Returnerar det nollbaserade indexet för den första förekomsten av den angivna shape i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape att leta upp i samlingen. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av shape i shape-samlingen om den hittas; annars, \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Skapar och returnerar en array som innehåller alla shapes.

**Returnerar:**
com.aspose.slides.IShape[] - En array av [IShape](../../com.aspose.slides/ishape)-objekt.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Skapar och returnerar en array som innehåller alla shapes i det angivna intervallet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Indexet för den första shape som ska returneras. |
| count | int | Antalet shapes som ska returneras. |

**Returnerar:**
com.aspose.slides.IShape[] - En array av [IShape](../../com.aspose.slides/ishape)-objekt.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Flyttar den angivna shape till en ny position inom shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade mål-indexet där shape kommer att placeras. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) att flytta inom samlingen. |
### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Flyttar de angivna shapes inom shape-samlingen, placerar dem startande vid det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade mål-indexet där den första angivna shape kommer att placeras; efterföljande shapes följer i den ordning som anges. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | En eller flera [IShape](../../com.aspose.slides/ishape)-instanser att flytta inom samlingen. |
### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Skapar en ny auto shape med standardformatering och lägger till den i slutet av shape-samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) för auto shape att lägga till. |
| x | float | x-koordinaten för figurens ram, i punkter. |
| y | float | y-koordinaten för figurens ram, i punkter. |
| width | float | bredden på figurens ram, i punkter. |
| height | float | höjden på figurens ram, i punkter. |

**Returnerar:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Det nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny autoform och lägger till den i slutet av formsamlingen, eventuellt med standardmallens formatinställningar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den autoform som ska läggas till. |
| x | float | x-koordinaten för figurens ram, i punkter. |
| y | float | y-koordinaten för figurens ram, i punkter. |
| width | float | bredden på figurens ram, i punkter. |
| height | float | höjden på figurens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallens stil (enkel stil, centrerad text och icke-tomt namn) på den nya formen; false för att skapa formen med alla egenskaper satta till sina standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Det nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Skapar en ny rektangulär autoform för att hysa matematiskt innehåll och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för figurens ram, i punkter. |
| y | float | y-koordinaten för figurens ram, i punkter. |
| width | float | bredden på figurens ram, i punkter. |
| height | float | höjden på figurens ram, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Det nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet, med standardmallens formatinställningar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där den nya autoformen ska sättas in. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den autoform som ska sättas in. |
| x | float | x-koordinaten för figurens ram, i punkter. |
| y | float | y-koordinaten för figurens ram, i punkter. |
| width | float | bredden på figurens ram, i punkter. |
| height | float | höjden på figurens ram, i punkter. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Det nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet, eventuellt med standardmallens formatinställningar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där autoformen ska sättas in. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den autoform som ska sättas in. |
| x | float | x-koordinaten för figurens ram, i punkter. |
| y | float | y-koordinaten för figurens ram, i punkter. |
| width | float | bredden på figurens ram, i punkter. |
| height | float | höjden på figurens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallens stil (inklusive icke-tomt namn, enkel stil och centrerad text); false för att skapa formen med alla egenskaper satta till sina standardvärden. |

**Returnerar:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Det nyss skapade [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram justeras automatiskt för att rymma alla former som läggs till.

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Det nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former och lägger till den bildade gruppen i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Den [ISvgImage](../../com.aspose.slides/isvgimage) som innehåller vektor-innehåll som ska konverteras till former. |
| x | float | x-koordinaten för gruppens ram, i punkter. |
| y | float | y-koordinaten för gruppens ram, i punkter. |
| width | float | bredden på gruppens ram, i punkter. |
| height | float | höjden på gruppens ram, i punkter. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Det nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Skapar en ny tom gruppform och sätter in den i formsamlingen på det angivna indexet. Gruppens ram justeras automatiskt för att rymma alla former som läggs till.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där gruppformen ska sättas in. |

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Det nyss skapade [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Skapar en ny kopplingsform med standardmallens format och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den kopplingsform som ska läggas till. |
| x | float | x-koordinaten för kopplingens ram, i punkter. |
| y | float | y-koordinaten för kopplingens ram, i punkter. |
| width | float | bredden på kopplingens ram, i punkter. |
| height | float | höjden på kopplingens ram, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Det nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny kopplingsform och lägger till den i slutet av formsamlingen, eventuellt med standardmallens format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den kopplingsform som ska skapas. |
| x | float | x-koordinaten för kopplingens ram, i punkter. |
| y | float | y-koordinaten för kopplingens ram, i punkter. |
| width | float | bredden på kopplingens ram, i punkter. |
| height | float | höjden på kopplingens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallens stil (icke-tomt namn, enkel stil); false för att skapa kopplingen med standardvärden för egenskaperna. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Det nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Skapar en ny kopplingsform och sätter in den i formsamlingen på det angivna indexet, med standardmallens format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där kopplingsformen ska sättas in. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den kopplingsform som ska sättas in. |
| x | float | x-koordinaten för kopplingens ram, i punkter. |
| y | float | y-koordinaten för kopplingens ram, i punkter. |
| width | float | bredden på kopplingens ram, i punkter. |
| height | float | höjden på kopplingens ram, i punkter. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Det nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Skapar en ny kopplingsform och sätter in den i formsamlingen på det angivna indexet, eventuellt med standardmallens format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där kopplingsformen ska sättas in. |
| shapeType | int | Den [ShapeType](../../com.aspose.slides/shapetype) för den kopplingsform som ska sättas in. |
| x | float | x-koordinaten för kopplingens ram, i punkter. |
| y | float | y-koordinaten för kopplingens ram, i punkter. |
| width | float | bredden på kopplingens ram, i punkter. |
| height | float | höjden på kopplingens ram, i punkter. |
| createFromTemplate | boolean | True för att tillämpa standardmallens stil (icke-tomt namn, enkel stil); false för att skapa kopplingen med standardvärden för egenskaperna. |

**Returnerar:**
[IConnector](../../com.aspose.slides/iconnector) - Det nyss skapade [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | int | Anger formtypen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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
| x | float | x-koordinaten för bildramen, i punkter. |
| y | float | y-koordinaten för bildramen, i punkter. |
| width | float | bredden på bildramen, i punkter. |
| height | float | höjden på bildramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bildramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Det nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Skapar en ny bildram som innehåller den angivna bilden och sätter in den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där bildramen ska sättas in. |
| shapeType | int | Anger formtypen som finns i [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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
| x | float | x-koordinaten för bildramen, i punkter. |
| y | float | y-koordinaten för bildramen, i punkter. |
| width | float | bredden på bildramen, i punkter. |
| height | float | höjden på bildramen, i punkter. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) som ska visas i bildramen. |

**Returnerar:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Det nyss skapade [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Skapar ett nytt bord och lägger till det i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | x-koordinaten för bordet, i punkter. |
| y | float | y-koordinaten för bordet, i punkter. |
| columnWidths | double[] | En array av double-värden som representerar bredden på bordets kolumner, i punkter. |
| rowHeights | double[] | En array av double-värden som representerar höjden på bordets rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Det nyss skapade [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där tabellen ska infogas. |
| x | float | X-koordinaten för tabellen, i punkter. |
| y | float | Y-koordinaten för tabellen, i punkter. |
| columnWidths | double[] | En array av double-värden som representerar bredden på tabellens kolumner, i punkter. |
| rowHeights | double[] | En array av double-värden som representerar höjden på tabellens rader, i punkter. |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Den nyss skapade [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort formen på det angivna indexet från formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för formen som ska tas bort. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Tar bort den första förekomsten av den angivna formen från formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att ta bort. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla former från formsamlingen.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Formen att klona. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |
| width | float | Bredden på den klonade formens ram, i punkter. |
| height | float | Höjden på den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredden och höjden på sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att klona. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller originalets position och storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att klona. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att klona. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |
| width | float | Bredden på den klonade formens ram, i punkter. |
| height | float | Höjden på den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredden och höjden på sourceShape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att klona. |
| x | float | X-koordinaten för den klonade formens ram, i punkter. |
| y | float | Y-koordinaten för den klonade formens ram, i punkter. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller originalets position och storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där den klonade formen ska infogas. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Den [IShape](../../com.aspose.slides/ishape) att klona. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Den nyss skapade [IShape](../../com.aspose.slides/ishape).