---
title: Output
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Az IWebDocument számára kimeneti elemek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/output/
---
**Öröklődés:**
java.lang.Object
```
public final class Output
```

Az IWebDocument számára kimeneti elemek gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Kimeneti elemet ad hozzá a kontextusobjektumhoz. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Kimeneti elemet ad hozzá a képhez. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Kimeneti elemet ad hozzá a képhez. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Kimeneti elemet ad hozzá a videóhoz. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Létrehozza és hozzáadja a megadott betűtípus kimeneti fájl elemét. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Kimeneti elemet ad hozzá a szövegtartalomhoz. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Erőforrást köt a kimeneti fájlhoz. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Visszaadja a megadott erőforrás útvonalát. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Kimeneti elemet ad hozzá a kontextusobjektumhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| templateKey | java.lang.String | A sablon kulcsa, amelyet a kontextusobjektum kimeneti előtti átalakításához használnak. |
| contextObject | TContextObject | Kontekstusobjektum. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a kontextusobjektumhoz.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Kimeneti elemet ad hozzá a képhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Kimeneti kép. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Kimeneti elemet ad hozzá a képhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| image | [IImage](../../com.aspose.slides/iimage) | Kimeneti kép. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a képhez.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Kimeneti elemet ad hozzá a videóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Kimeneti videó. |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objektum a videóhoz.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Létrehozza és hozzáadja a megadott betűtípus kimeneti fájl elemét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | A fájlútvonal, ahol a betűtípus kimenet mentésre kerül. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A kimenetre írandó betűtípus adat. |
| fontStyle | int | A betűtípus stílusa (pl. Regular, Bold, Italic). |

**Visszatérési érték:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Egy [IOutputFile](../../com.aspose.slides/ioutputfile) példány a generált betűtípushoz.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Kimeneti elemet ad hozzá a szövegtartalomhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | java.lang.String | Kimeneti útvonal. |
| textContent | java.lang.String | Kimeneti tartalom. |

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


Visszaadja a megadott erőforrás útvonalát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Erőforrás objektum. |

**Visszatérési érték:**
java.lang.String - Erőforrás útvonal.