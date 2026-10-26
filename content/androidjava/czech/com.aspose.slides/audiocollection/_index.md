---
title: AudioCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci vložených audio souborů.
type: docs
url: /cs/com.aspose.slides/audiocollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Reprezentuje kolekci vložených audio souborů.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet audio souborů v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Přidá kopii audio souboru z jiné prezentace. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Vytvoří a přidá audio do prezentace ze streamu. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Vytvoří a přidá audio do prezentace ze streamu. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Vytvoří a přidá audio do prezentace z pole bajtů. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje audia do zadaného pole počínaje zadaným indexem. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```

Vrací počet audio souborů v kolekci. Pouze pro čtení int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Přidá kopii audio souboru z jiné prezentace.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Zdrojové audio. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Vytvoří a přidá audio do prezentace ze streamu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se audio přidá. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Vytvoří a přidá audio do prezentace ze streamu.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se audio přidá. |
| loadingStreamBehavior | int | Chování, které bude na stream aplikováno. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Vytvoří a přidá audio do prezentace z pole bajtů.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audioData | byte[] | Bajty audio. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje audia do zadaného pole počínaje zadaným indexem.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - java.util.Iterator pro celou kolekci.