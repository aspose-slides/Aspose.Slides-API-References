---
title: Output
second_title: Aspose.Slides for Android Java API referencia
description: Az IWebDocument számára kimeneti elemek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/output/
---
**Öröklés:**
java.lang.Object
```
public final class Output
```

Képviseli a kimeneti elemek gyűjteményét az IWebDocument számára.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Hozzáad egy kimeneti elemet a kontextusobjektumhoz. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Hozzáad egy kimeneti elemet a képhez. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Hozzáad egy kimeneti elemet a képhez. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Hozzáad egy kimeneti elemet a videóhoz. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Hozzáad egy kimeneti elemet a hanghoz. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Létrehoz és hozzáad egy kimeneti fájl elemet a megadott betűtípushoz. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Hozzáad egy kimeneti elemet a szövegtartalomhoz. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Erőforrást köt a kimeneti fájlhoz. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Visszaadja az adott erőforrás útvonalát. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Hozzáad egy kimeneti elemet a kontextusobjektumhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| templateKey | java.lang.String | A sablon kulcsa, amely a kontextusobjektum kimeneti átalakításához használatos. |
| contextObject | TContextObject | Kontekstusobjektum. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a kontextusobjektumhoz.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Hozzáad egy kimeneti elemet a képfájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Kimeneti kép. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Hozzáad egy kimeneti elemet a képfájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IImage](../../com.aspose.slides/iimage) | Kimeneti kép. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Hozzáad egy kimeneti elemet a videóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Kimeneti videó. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a videóhoz.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


Hozzáad egy kimeneti elemet a hanghoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Kimeneti hang. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a hanghoz.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Létrehoz és hozzáad egy kimeneti fájl elemet a megadott betűtípushoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A fájl útvonala, ahol a betűtípus kimenete el lesz mentve. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A kimenetre írandó betűtípus adat. |
| fontStyle | int | A betűtípus stílusa (pl. Regular, Bold, Italic). |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Egy [IOutputFile](../../com.aspose.slides/ioutputfile) példány a generált betűtípushoz.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Hozzáad egy kimeneti elemet a szövegtartalomhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| textContent | java.lang.String | Kimeneti tartalom. |

**Visszatér:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a szövegtartalomhoz.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Erőforrást köt a kimeneti fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Kimeneti fájl. |
| obj | java.lang.Object | Erőforrás objektum. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Visszaadja az adott erőforrás útvonalát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Erőforrás objektum. |

**Visszatér:**
java.lang.String - Erőforrás útvonal.