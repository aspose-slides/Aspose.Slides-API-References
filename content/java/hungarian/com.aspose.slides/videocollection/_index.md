---
title: VideoCollection
second_title: Aspose.Slides Java API Referencia
description: A Video objektumok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/videocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

A Video objektumok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő videofájlok számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexnél lévő elemet. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Videofájl másolatát adja hozzá egy másik prezentációból. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Videót hoz létre és ad hozzá a prezentációhoz egy folyam (stream) segítségével. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Videót hoz létre és ad hozzá a prezentációhoz egy bájttömbből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Videókat másol a megadott tömbbe a megadott indextől kezdve. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő videofájlok számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Lekéri a megadott indexnél lévő elemet. Csak olvasható [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Videofájl másolatát adja hozzá egy másik prezentációból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Forrás videó. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Videót hoz létre és ad hozzá a prezentációhoz folyamról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A folyam, amelyből a videófájlt hozzáadja. |
| loadingStreamBehavior | int | Az a viselkedés, amely a folyamra lesz alkalmazva. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Videót hoz létre és ad hozzá a prezentációhoz bájttömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| videoData | byte[] | Videó bájtok. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Videókat másol a megadott tömbbe a megadott indextől kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tömb. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Egy java.util.Iterator a teljes gyűjteményhez.