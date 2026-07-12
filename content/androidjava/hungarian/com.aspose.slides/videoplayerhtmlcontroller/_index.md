---
title: VideoPlayerHtmlController
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Ez az osztály lehetővé teszi a videó- és hangfájlok HTML-be való exportálását.
type: docs
url: /hu/com.aspose.slides/videoplayerhtmlcontroller/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)  
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Ez az osztály lehetővé teszi videó- és hangfájlok exportálását HTML-be

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Létrehoz egy új példányt a vezérlőből |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |

### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```

Létrehoz egy új példányt a vezérlőből

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A útvonal, ahol a videó- és hangfájlok generálva lesznek |
| fileName | java.lang.String | A HTML fájl neve |
| baseUri | java.lang.String | Az alap URI, amely a hivatkozások generálásához lesz használva |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Az html dokumentum fejlécének írásához hívják. Egy prezentációkonverziónként egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Az html dokumentum láblécének írásához hívják. Egy prezentációkonverziónként egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Az html dia fejlécének írásához hívják. Minden dián egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Az html dia láblécének írásához hívják. Minden dián egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

A shape renderelése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generator-ba, a jelenlegi dia kép generálása befejeződik, a hozzáadott html töredék beillesztődik, és egy új kép indul a korábbi felett.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

A shape renderelése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generator-ba, a jelenlegi dia kép generálása befejeződik, a hozzáadott html töredék beillesztődik, és egy új kép indul a korábbi felett.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

Ez a függvény a shape SVG-re történő renderelése előtt hívódik, hogy a felhasználó szabályozhassa a keletkező SVG-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Meghatározza, hogy hol kell tárolni az objektumot. Ez a metódus minden objektum-azonosítóhoz egyszer hívódik. Nem garantált, hogy nem lesz két objektum ugyanazzal az adat, semanticName és contentType értékkel, de eltérő azonosítóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Visszatérési érték:**
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

Egy URL-t ad vissza egy külső objektumhoz. Ez a metódus mindig akkor hívódik, ha #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) értéket adott vissza, és akkor is hívható, ha #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) értéket adott vissza, de a beágyazás lehetetlen. Többször is hívható ugyanazzal az objektum-azonosítóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Visszatérési érték:**
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

Külső objektumot ment.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |