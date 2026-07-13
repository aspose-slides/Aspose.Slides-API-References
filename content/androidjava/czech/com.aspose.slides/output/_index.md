---
title: Output
second_title: Aspose.Slides pro Android přes Java API Reference
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
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Vytvoří a přidá prvek výstupního souboru pro zadané písmo. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Přidá výstupní prvek pro textový obsah. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Váže zdroj k výstupnímu souboru. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Vrací cestu k danému zdroji. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Přidá výstupní prvek pro objekt kontextu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| templateKey | java.lang.String | Klíč šablony používaný pro transformaci objektu kontextu před výstupem. |
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
| path | java.lang.String | Cesta výstupu. |
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
| path | java.lang.String | Cesta výstupu. |
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
| path | java.lang.String | Cesta výstupu. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Vytvoří a přidá prvek výstupního souboru pro zadané písmo.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta souboru, kde bude výstup písma uložen. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Data písma, která budou zapsána do výstupu. |
| fontStyle | int | Styl písma (např. Regular, Bold, Italic). |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Instanci [IOutputFile](../../com.aspose.slides/ioutputfile) pro vygenerované písmo.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Přidá výstupní prvek pro textový obsah.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta výstupu. |
| textContent | java.lang.String | Obsah k výstupu. |

**Vrací:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objekt pro textový obsah.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Váže zdroj k výstupnímu souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Výstupní soubor. |
| obj | java.lang.Object | Objekt zdroje. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Vrací cestu k danému zdroji.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt zdroje. |

**Vrací:**
java.lang.String - Cesta ke zdroji.