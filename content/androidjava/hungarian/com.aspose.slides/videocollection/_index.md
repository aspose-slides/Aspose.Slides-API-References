---
title: VideoCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Videó objektumok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/videocollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Videó objektumok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | A gyűjteményben lévő videófájlok számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Egy másik prezentációból származó videófájl másolatát adja hozzá. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Videót hoz létre és ad hozzá egy prezentációhoz egy folyam (stream) alapján. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Videót hoz létre és ad hozzá egy prezentációhoz egy byte tömbből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Videókat másol a megadott tömbbe a megadott indextől kezdve. |
| [isSynchronized()](#isSynchronized--) | Értéket ad vissza, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Szinkronizációs gyökeret ad vissza. |
| [iterator()](#iterator--) | Egy enumerátort ad vissza, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Egy Java iterátort ad vissza a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

A gyűjteményben lévő videófájlok számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [IVideo](../../com.aspose.slides/ivideo).

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

Egy másik prezentációból származó videófájl másolatát adja hozzá.

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

Videót hoz létre és ad hozzá egy prezentációhoz egy folyam (stream) alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A folyam, amelyből a videófájlt hozzáadja. |
| loadingStreamBehavior | int | A viselkedés, amely a folyamra lesz alkalmazva. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Videót hoz létre és ad hozzá egy prezentációhoz egy byte tömbből.

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

Értéket ad vissza, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Szinkronizációs gyökeret ad vissza. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Egy enumerátort ad vissza, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Egy Java iterátort ad vissza a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Egy java.util.Iterator a teljes gyűjteményhez.