---
title: ImageCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: PPImage gyűjteményt reprezentál.
type: docs
url: /hu/com.aspose.slides/imagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage gyűjteményt képviseli.
## Metódusok

| Method | Description |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő képek számát. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Képmásolatot ad hozzá egy másik prezentációból. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Képet ad hozzá egy prezentációhoz. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Képet ad hozzá egy prezentációhoz egy folyamatról. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Létrehoz és hozzáad egy képet egy prezentációhoz egy folyamatról. |
| [addImage(byte[] buffer)](#addImage-byte---) | Képet ad hozzá egy prezentációhoz a megadott pufferből. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Képet ad hozzá egy prezentációhoz SVG objektumból. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végig iterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterator-t a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### size() {#size--}
```
public final int size()
```


Visszaadja a gyűjteményben lévő képek számát. Csak olvasható  int .

**Visszatérési érték:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


A megadott indexű elemet adja vissza. Csak olvasható [IPPImage](../../com.aspose.slides/ippimage).

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


Képmásolatot ad hozzá egy másik prezentációból.

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


Képet ad hozzá egy prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | A hozzáadandó kép. |

--------------------

Ez a metódus a WMF/EMF meta-fájlokat raszteres PNG képpé konvertálja, mielőtt a prezentációba illesztené.

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Képet ad hozzá egy prezentációhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A kép hozzáadásához használt adatfolyam. |

--------------------

Ez a metódus WMF/EMF meta-fájlokat képes hozzáadni a prezentációhoz konvertálás nélkül.

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Létrehoz és hozzáad egy képet egy prezentációhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A kép hozzáadásához használt adatfolyam. |
| loadingStreamBehavior | int | A viselkedés, amely a folyamatra lesz alkalmazva. |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Képet ad hozzá egy prezentációhoz a megadott pufferből.

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


Képet ad hozzá egy prezentációhoz SVG objektumból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG kép objektum [ISvgImage](../../com.aspose.slides/isvgimage) |

**Visszatérési érték:**  
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Visszaad egy enumerátort, amely végig iterál a gyűjteményen.

**Visszatérési érték:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Visszaad egy java iterator-t a teljes gyűjteményhez.

**Visszatérési érték:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható  boolean .

**Visszatérési érték:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható  Object .

**Visszatérési érték:**  
java.lang.Object