---
title: PictureFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Rahmen mit einem Bild darin dar.
type: docs
url: /de/com.aspose.slides/pictureframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Stellt einen Rahmen mit einem Bild darin dar.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Fügt der Folie ein Audio-Frame mit einer angegebenen Position und Größe hinzu.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Fügt ein Bild zu den Präsentationsressourcen hinzu.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Setzt das Bild für das Audio-Frame.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Speichert die modifizierte Präsentation auf die Festplatte
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Gibt die Sperren der Form zurück. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Gibt das PictureFillFormat-Objekt für ein PictureFrame zurück. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Gibt die Skalierung der Höhe (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Gibt die Skalierung der Höhe (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Gibt die Skalierung der Breite (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Gibt die Skalierung der Breite (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. |
| [isCameo()](#isCameo--) | Ermittelt, ob das PictureFrame ein Cameo-Objekt ist oder nicht. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Gibt die Sperren der Form zurück. Schreibgeschützt [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Rückgabe:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Gibt den AutoShape-Typ für ein PictureFrame zurück oder legt ihn fest. Alle zulässigen Elemente des Satzes [ShapeType](../../com.aspose.slides/shapetype) sind erlaubt, mit Ausnahme aller Linienarten:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Rückgabe:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Gibt den AutoShape-Typ für ein PictureFrame zurück oder legt ihn fest. Alle zulässigen Elemente des Satzes [ShapeType](../../com.aspose.slides/shapetype) sind erlaubt, mit Ausnahme aller Linienarten:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Gibt das PictureFillFormat-Objekt für ein PictureFrame zurück. Schreibgeschützt [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Gibt die Skalierung der Höhe (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben  float .

**Rückgabe:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Gibt die Skalierung der Höhe (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Gibt die Skalierung der Breite (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben  float .

**Rückgabe:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Gibt die Skalierung der Breite (relativ zur Originalbildgröße) des PictureFrames zurück oder legt sie fest. Der Wert 1,0 entspricht 100 %. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Ermittelt, ob das PictureFrame ein Cameo-Objekt ist oder nicht. Nur lesbar boolean.

**Rückgabe:**
boolean