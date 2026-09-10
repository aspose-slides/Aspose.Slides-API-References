---
title: Output
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci výstupních prvků pro IWebDocument.
type: docs
url: /cs/com.aspose.slides/output/
---
**Dědičnost:**
java.lang.Object
```
public final class Output
```

Představuje kolekci výstupních prvků pro IWebDocument.

## Metody

| Metoda | Popis |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Adds an output element for the audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Přidá výstupní prvek pro objekt kontextu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| templateKey | java.lang.String | Klíč šablony používané pro transformaci objektu kontextu před výstupem. |
| contextObject | TContextObject | Objekt kontextu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro objekt kontextu.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Přidá výstupní prvek pro obrázek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obrázek k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro obrázek.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Přidá výstupní prvek pro obrázek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro obrázek.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Přidá výstupní prvek pro video.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Přidá výstupní prvek pro audio.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Vytvoří a přidá výstupní souborový prvek pro zadané písmo.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta k souboru, kam bude výstup písma uložen. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Data písma, která budou zapsána do výstupu. |
| fontStyle | int | Styl písma (např. Regular, Bold, Italic). |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - An [IOutputFile](../../com.aspose.slides/ioutputfile) instance pro vygenerované písmo.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Přidá výstupní prvek pro textový obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Výstupní cesta. |
| textContent | java.lang.String | Obsah k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro textový obsah.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Připojí prostředek k výstupnímu souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Výstupní soubor. |
| obj | java.lang.Object | Objekt prostředku. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Vrací cestu pro daný prostředek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt prostředku. |

**Vrací:**
java.lang.String - Cesta prostředku.