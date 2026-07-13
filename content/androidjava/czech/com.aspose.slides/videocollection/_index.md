---
title: VideoCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje kolekci objektů Video.
type: docs
url: /cs/com.aspose.slides/videocollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Představuje kolekci objektů Video.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet video souborů v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Přidá kopii video souboru z jiné prezentace. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Vytvoří a přidá video do prezentace ze streamu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Vytvoří a přidá video do prezentace z pole bajtů. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje videa do zadaného pole počínaje zadaným indexem. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```


Vrací počet video souborů v kolekci. Pouze ke čtení int.

**Návratová hodnota:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze ke čtení [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
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

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Vytvoří a přidá video do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se má přidat video soubor. |
| loadingStreamBehavior | int | Chování, které bude použito pro stream. |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidáno [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


Vytvoří a přidá video do prezentace z pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| videoData | byte[] | Bity videa. |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje videa do zadaného pole počínaje zadaným indexem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze ke čtení Object.

**Návratová hodnota:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - IGenericEnumerator, který lze použít k iteraci kolekce.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator pro celou kolekci.