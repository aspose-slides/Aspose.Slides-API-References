---
title: AudioCollection
second_title: Aspose.Slides a Java API referencia
description: Beágyazott audio fájlok gyűjteményét ábrázolja.
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

Beágyazott audio fájlok gyűjteményét ábrázolja.
## Módszerek

| Method | Description |
| --- | --- |
| [size()](#size--) | Visszatér a gyűjteményben lévő audio fájlok számával. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Hozzáad egy audio fájl másolata egy másik bemutatóból. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy folyamatról. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy folyamatról. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy byte tömbből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a hangokat a megadott tömbbe a megadott indextől kezdve. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér a szinkronizáció gyökérével. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```


Visszatér a gyűjteményben lévő audio fájlok számával. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


Lekéri a megadott indexű elemet. Csak olvasható [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


Hozzáad egy audio fájl másolatát egy másik bemutatóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Forrás audio. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Folyam, amelyből az audio-t hozzáadja. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Folyam, amelyből a videó audio-t hozzáadja. |
| loadingStreamBehavior | int | A viselkedés, amely a folyamra lesz alkalmazva. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Létrehoz és hozzáad egy audio-t egy bemutatóhoz egy byte tömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audioData | byte[] | Audio byte-ok. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a hangokat a megadott tömbbe a megadott indextől kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tömb. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Visszatér egy enumerátorral, amely végigjárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Egy java.util.Iterator a teljes gyűjteményhez.