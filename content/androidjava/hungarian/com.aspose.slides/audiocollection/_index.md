---
title: AudioCollection
second_title: Aspose.Slides Androidra Java API referencia
description: Beágyazott audiofájlok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/audiocollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Beágyazott audiofájlok gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő audiofájlok számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Hozzáad egy audiofájl másolatot egy másik prezentációból. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Létrehoz és hozzáad egy audiofájlt egy prezentációhoz adatfolyamból. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Létrehoz és hozzáad egy audiofájlt egy prezentációhoz adatfolyamból. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Létrehoz és hozzáad egy audiofájlt egy prezentációhoz byte tömbből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Másolja az audiofájlokat a megadott tömbbe a megadott indextől kezdve. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő audiofájlok számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Lekéri az elemet a megadott indexnél. Csak olvasható [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Hozzáad egy audiofájlt másolatot egy másik prezentációból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Forrás audio. |

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Létrehoz és hozzáad egy audiofájlt egy prezentációhoz adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Audio hozzáadásához használt adatfolyam. |

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Létrehoz és hozzáad egy audiofájlt egy prezentációhoz adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Audio hozzáadásához használt adatfolyam. |
| loadingStreamBehavior | int | A viselkedés, amely az adatfolyamra lesz alkalmazva. |

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Létrehoz és hozzáad egy audiofájlt egy prezentációhoz byte tömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audioData | byte[] | Audio bájtok. |

**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Másolja az audiofájlokat a megadott tömbbe a megadott indextől kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tömb. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.