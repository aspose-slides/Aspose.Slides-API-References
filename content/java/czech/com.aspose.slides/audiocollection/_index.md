---
title: AudioCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci vložených zvukových souborů.
type: docs
url: /cs/com.aspose.slides/audiocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Represents a collection of embedded audio files.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet zvukových souborů v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Přidá kopii zvukového souboru z jiné prezentace. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Vytvoří a přidá zvuk do prezentace ze streamu. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Vytvoří a přidá zvuk do prezentace ze streamu. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Vytvoří a přidá zvuk do prezentace z pole bytů. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje zvuky do určeného pole počínaje zadaným indexem. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```


Vrací počet zvukových souborů v kolekci. **Pouze pro čtení int.**

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


Získá prvek na zadaném indexu. **Pouze pro čtení [IAudio](../../com.aspose.slides/iaudio).**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


Přidá kopii zvukového souboru z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Zdrojový zvuk. |

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio) - Přidaný zvuk.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


Vytvoří a přidá zvuk do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá zvuk. |

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio) - Přidaný zvuk.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Vytvoří a přidá zvuk do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá audio. |
| loadingStreamBehavior | int | Chování, které bude použito na stream. |

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio) - Přidaný zvuk.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Vytvoří a přidá zvuk do prezentace z pole bytů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audioData | byte[] | Audio bajty. |

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio) - Přidaný zvuk.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopíruje zvuky do určeného pole počínaje zadaným indexem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). **Pouze pro čtení boolean.**

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. **Pouze pro čtení Object.**

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.