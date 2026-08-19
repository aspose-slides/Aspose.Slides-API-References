---
title: IImageCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci PPImage.
type: docs
url: /cs/com.aspose.slides/iimagecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Represents collection of PPImage.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns image by its index. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Add an image to a presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Add an image to a presentation from stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Creates and adds an image to a presentation from stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adds a copy of an image from an another presentation. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Add an image to a presentation from SVG object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Vrací obrázek podle jeho indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Obrázek.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Přidá obrázek do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek k přidání.

--------------------

This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá obrázek.

--------------------

This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Vytvoří a přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá obrázek. |
| loadingStreamBehavior | int | Chování, které bude na stream použito. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Přidá obrázek do prezentace ze specifikovaného bufferu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | byte[] | Vyrovnávací paměť. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Přidá kopii obrázku z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Zdrojový obrázek. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Přidá obrázek do prezentace z objektu SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objekt SVG obrázku [ISvgImage](../../com.aspose.slides/isvgimage) |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.