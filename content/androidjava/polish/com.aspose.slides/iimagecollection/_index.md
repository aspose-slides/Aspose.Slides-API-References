---
title: IImageCollection
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Reprezentuje kolekcję PPImage.
type: docs
url: /pl/com.aspose.slides/iimagecollection/
---
**Wszystkie implementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Reprezentuje kolekcję PPImage.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca obraz według jego indeksu. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Dodaje obraz do prezentacji. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Dodaje obraz do prezentacji ze strumienia. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Tworzy i dodaje obraz do prezentacji ze strumienia. |
| [addImage(byte[] buffer)](#addImage-byte---) | Dodaje obraz do prezentacji z określonego bufora. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Dodaje kopię obrazu z innej prezentacji. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Dodaje obraz do prezentacji z obiektu SVG. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Zwraca obraz według jego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Obraz.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Dodaje obraz do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obraz do dodania. |

--------------------

Ta metoda konwertuje pliki metafile WMF/EMF na rastrowy obraz PNG przed wstawieniem do prezentacji. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Dodaje obraz do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać obraz. |

--------------------

Ta metoda może dodawać pliki metafile WMF/EMF do prezentacji bez konwertowania ich na rastrowy obraz PNG. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Tworzy i dodaje obraz do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać plik obrazu. |
| loadingStreamBehavior | int | Zachowanie, które zostanie zastosowane do strumienia. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Dodaje obraz do prezentacji z określonego bufora.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | byte[] | Bufor. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Dodaje kopię obrazu z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Źródłowy obraz. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Dodaje obraz do prezentacji z obiektu SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Obiekt obrazu SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.