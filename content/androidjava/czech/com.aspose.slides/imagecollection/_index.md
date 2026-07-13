---
title: ImageCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Zastupuje kolekci PPImage.
type: docs
url: /cs/com.aspose.slides/imagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Representuje kolekci PPImage.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet obrázků ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Přidá kopii obrázku z jiné prezentace. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Přidá obrázek do prezentace. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Přidá obrázek do prezentace ze streamu. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Vytvoří a přidá obrázek do prezentace ze streamu. |
| [addImage(byte[] buffer)](#addImage-byte---) | Přidá obrázek do prezentace z určeného bufferu. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Přidá obrázek do prezentace z objektu Svg. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky ze sbírky do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke sbírce synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### size() {#size--}
```
public final int size()
```


Vrací počet obrázků ve sbírce. Pouze pro čtení  int .

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze pro čtení [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Přidá kopii obrázku z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Zdrojový obrázek. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Přidá obrázek do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek k přidání.

--------------------

Tato metoda převádí WMF/EMF metahodnoty na rastrový PNG obrázek před vložením do prezentace. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá obrázek.

--------------------

Tato metoda může přidat WMF/EMF metahodnoty do prezentace bez jejich převodu na rastrový PNG obrázek. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Vytvoří a přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá soubor obrázku. |
| loadingStreamBehavior | int | Chování, které bude použito na stream. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidáno [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Přidá obrázek do prezentace z určeného bufferu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Přidá obrázek do prezentace z objektu Svg.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objekt SVG obrázku [ISvgImage](../../com.aspose.slides/isvgimage) |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje všechny prvky ze sbírky do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Pouze pro čtení  boolean .

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze pro čtení  Object .

**Vrací:**
java.lang.Object