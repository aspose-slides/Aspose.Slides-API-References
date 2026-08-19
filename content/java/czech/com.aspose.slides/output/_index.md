---
title: Output
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci výstupních prvků pro IWebDocument.
type: docs
url: /cs/com.aspose.slides/output/
---
**Dědičnost:**
java.lang.Object
```
public final class Output
```

Reprezentuje kolekci výstupních prvků pro IWebDocument.
## Metody

| Metoda | Popis |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Přidá výstupní prvek pro objekt kontextu. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Přidá výstupní prvek pro obrázek. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Přidá výstupní prvek pro obrázek. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Přidá výstupní prvek pro video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Přidá výstupní prvek pro audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Vytvoří a přidá výstupní souborový prvek pro zadané písmo. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Přidá výstupní prvek pro textový obsah. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Naváže prostředek k výstupnímu souboru. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Vrátí cestu k danému prostředku. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Přidá výstupní prvek pro objekt kontextu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| templateKey | java.lang.String | Klíč šablony použité pro transformaci objektu kontextu před výstupem. |
| contextObject | TContextObject | Objekt kontextu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro objekt kontextu.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Přidá výstupní prvek pro obrázek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek k výstupu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro obrázek.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Přidá výstupní prvek pro obrázek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek k výstupu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro obrázek.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Přidá výstupní prvek pro video.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video k výstupu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


Přidá výstupní prvek pro audio.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio k výstupu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Vytvoří a přidá výstupní souborový prvek pro zadané písmo.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta souboru, kam bude uložen výstup písma. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Data písma, která mají být zapsána do výstupu. |
| fontStyle | int | Styl písma (např. Regular, Bold, Italic). |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Instance [IOutputFile](../../com.aspose.slides/ioutputfile) pro vygenerované písmo.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Přidá výstupní prvek pro textový obsah.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| textContent | java.lang.String | Obsah k výstupu. |

**Návratová hodnota:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro textový obsah.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Naváže prostředek k výstupnímu souboru.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Výstupní soubor. |
| obj | java.lang.Object | Objekt prostředku. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Vrací cestu k danému prostředku.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objekt prostředku. |

**Návratová hodnota:**
java.lang.String - Cesta k prostředku.