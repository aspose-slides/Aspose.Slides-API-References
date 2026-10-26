---
title: Output
second_title: Aspose.Slides Java API referenciája
description: Az IWebDocument számára a kimeneti elemek egy gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/output/
---
**Öröklés:**
java.lang.Object
```
public final class Output
```

Az IWebDocument számára kimeneti elemek egy gyűjteményét jelenti.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Kimeneti elemet ad a kontextus objektumhoz. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Kimeneti elemet ad a képhez. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Kimeneti elemet ad a képhez. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Kimeneti elemet ad a videóhoz. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Kimeneti elemet ad az audióhoz. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Létrehozza és hozzáad egy kimeneti fájl elemet a megadott betűtípushoz. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Kimeneti elemet ad a szövegtartalomhoz. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Erőforrást köt a kimeneti fájlhoz. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Visszaadja az adott erőforrás útvonalát. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Kimeneti elemet ad a kontextus objektumhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| templateKey | java.lang.String | A sablon kulcsa a kontextus objektum kimenetre való átalakítása előtt. |
| contextObject | TContextObject | Kontekstus objektum. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a kontextus objektumhoz.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Kimeneti elemet ad a képhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A kimenetre írandó kép. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Kimeneti elemet ad a képhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IImage](../../com.aspose.slides/iimage) | A kimenetre írandó kép. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Kimeneti elemet ad a videóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| video | [IVideo](../../com.aspose.slides/ivideo) | A kimenetre írandó videó. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a videóhoz.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Kimeneti elemet ad az audióhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | A kimenetre írandó audió. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum az audióhoz.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Létrehozza és hozzáad egy kimeneti fájl elemet a megadott betűtípushoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A fájl útvonala, ahova a betűtípus kimenet mentésre kerül. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A kimenetre írandó betűtípus adat. |
| fontStyle | int | A betűtípus stílusa (pl. Regular, Bold, Italic). |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Egy [IOutputFile](../../com.aspose.slides/ioutputfile) példány a létrehozott betűtípushoz.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Kimeneti elemet ad a szövegtartalomhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| textContent | java.lang.String | A kimenetre írandó tartalom. |

**Visszatérési érték:**
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

**Visszatérési érték:**
java.lang.String - Erőforrás útvonala.