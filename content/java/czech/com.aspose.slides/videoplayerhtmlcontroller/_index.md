---
title: VideoPlayerHtmlController
second_title: Aspose.Slides pro Java – referenční příručka
description: Třída umožňuje export videí a audio souborů do HTML
type: docs
url: /cs/com.aspose.slides/videoplayerhtmlcontroller/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Tato třída umožňuje export videí a audio souborů do HTML
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Vytvoří novou instanci řadiče |
## Metody

| Metoda | Popis |
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


Vytvoří novou instanci řadiče

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta, kde budou generovány video a audio soubory |
| fileName | java.lang.String | Název souboru HTML |
| baseUri | java.lang.String | Základní URI, která bude použita pro generování odkazů |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Voláno pro zápis hlavičky html dokumentu. Voláno jednou při každém převodu prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Voláno pro zápis patičky html dokumentu. Voláno jednou při každém převodu prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Voláno pro zápis hlavičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Voláno pro zápis patičky html snímku. Voláno jednou pro každý snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce něco zapíše do generátoru, aktuální generování obrázku snímku bude ukončeno, vložený html fragment bude přidán a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce něco zapíše do generátoru, aktuální generování obrázku snímku bude ukončeno, vložený html fragment bude přidán a nový obrázek bude zahájen nad předchozím.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Tato funkce je volána před vykreslením tvaru do SVG, aby uživatel mohl ovládat výsledné SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Určuje, kde by měl být objekt uložen. Tato metoda je volána jednou pro každé ID objektu. Není zaručeno, že nebudou existovat dva objekty se stejnými daty, semanticName a contentType, ale s různým ID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Vrací:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


Vrací URL na externí objekt. Tato metoda je vždy volána, pokud #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) a může být volána, pokud #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), ale vkládání je nemožné. Může být volána vícekrát pro stejné ID objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Vrací:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Uloží externí objekt.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |