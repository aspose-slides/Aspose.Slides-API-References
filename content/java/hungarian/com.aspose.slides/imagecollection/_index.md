---
title: ImageCollection
second_title: Aspose.Slides Java API referencia
description: PPImage gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imagecollection/
---
**Öröklés:**  
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)  
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage gyűjteményét képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő képek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Képmásolatot ad hozzá egy másik bemutatóból. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Képet ad egy bemutatóhoz. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Képet ad egy bemutatóhoz egy adatfolyamból. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Létrehozza és hozzáadja a képet egy bemutatóhoz egy adatfolyamból. |
| [addImage(byte[] buffer)](#addImage-byte---) | Képet ad egy bemutatóhoz a megadott pufferből. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Képet ad egy bemutatóhoz SVG objektumból. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő képek számát. Csak olvasható int .

**Visszatérési érték:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [IPPImage](../../com.aspose.slides/ippimage).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Képmásolatot ad hozzá egy másik bemutatóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Forráskép. |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Képet ad egy bemutatóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hozzáadandó kép. |

--------------------

Ez a metódus WMF/EMF metafájlokat raszteres PNG képpé konvertál, mielőtt beilleszti a bemutatóba.

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Képet ad egy bemutatóhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Adatfolyam, amelyből a képet hozzáadja. |

--------------------

Ez a metódus WMF/EMF metafájlokat hozzáadhat a bemutatóhoz anélkül, hogy raszteres PNG képpé konvertálná őket.

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Létrehozza és hozzáadja a képet egy bemutatóhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Adatfolyam, amelyből a képfájlt hozzáadja. |
| loadingStreamBehavior | int | A viselkedés, amelyet az adatfolyamra alkalmaznak. |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Képet ad egy bemutatóhoz a megadott pufferből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | byte[] | Puffer. |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Képet ad egy bemutatóhoz SVG objektumból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG képobjektum [ISvgImage](../../com.aspose.slides/isvgimage) |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatérési érték:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator, amelyet a gyűjtemény bejárásához használhat.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean .

**Visszatérési érték:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object .

**Visszatérési érték:**  
java.lang.Object