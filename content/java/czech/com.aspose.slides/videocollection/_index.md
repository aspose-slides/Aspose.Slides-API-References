---
title: VideoCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci objektů Video.
type: docs
url: /cs/com.aspose.slides/videocollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Representuje kolekci objektů Video.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet video souborů ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Přidá kopii video souboru z jiné prezentace. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Vytvoří a přidá video do prezentace ze streamu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Vytvoří a přidá video do prezentace z pole bajtů. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje videa do určeného pole počínaje od zadaného indexu. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```

Vrací počet video souborů ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Přidá kopii video souboru z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Zdrojové video. |

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Vytvoří a přidá video do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidává video soubor. |
| loadingStreamBehavior | int | Chování, které bude aplikováno na stream. |

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Vytvoří a přidá video do prezentace z pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| videoData | byte[] | Bajty videa. |

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje videa do určeného pole počínaje od zadaného indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator pro celou kolekci.