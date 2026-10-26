---
title: ImageCollection
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje kolekcję PPImage.
type: docs
url: /pl/com.aspose.slides/imagecollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Reprezentuje kolekcję PPImage.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę obrazów w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Dodaje kopię obrazu z innej prezentacji. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Dodaje obraz do prezentacji. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Dodaje obraz do prezentacji ze strumienia. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Tworzy i dodaje obraz do prezentacji ze strumienia. |
| [addImage(byte[] buffer)](#addImage-byte---) | Dodaje obraz do prezentacji z określonego bufora. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Dodaje obraz do prezentacji z obiektu Svg. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Javy dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę obrazów w kolekcji. Tylko do odczytu int .

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Pobiera element pod określonym indeksem. Tylko do odczytu [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Dodaje kopię obrazu z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Obraz źródłowy. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Dodaje obraz do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obraz do dodania. |

--------------------

Ta metoda konwertuje pliki metafile WMF/EMF do rastrowego obrazu PNG przed wstawieniem do prezentacji. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Dodaje obraz do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać obraz. |

--------------------

Ta metoda może dodać pliki metafile WMF/EMF do prezentacji bez konwertowania ich do rastrowego obrazu PNG. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
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
public final IPPImage addImage(byte[] buffer)
```

Dodaje obraz do prezentacji z określonego bufora.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | byte[] | Bufor. |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Dodaje obraz do prezentacji z obiektu Svg.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Obiekt obrazu Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Dodany obraz.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Zwraca iterator Javy dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean .

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object .

**Zwraca:**
java.lang.Object