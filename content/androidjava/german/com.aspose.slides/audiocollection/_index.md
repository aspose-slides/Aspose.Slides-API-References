---
title: AudioCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung eingebetteter Audiodateien dar.
type: docs
url: /de/com.aspose.slides/audiocollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Stellt eine Sammlung eingebetteter Audiodateien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Audiodateien in der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Erstellt und fügt ein Audio aus einem Byte-Array zu einer Präsentation hinzu. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert Audios in das angegebene Array, beginnend am angegebenen Index. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Audiodateien in der Sammlung zurück. Nur lesbarer int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Quellaudio. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem das Audio hinzugefügt wird. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem das Audio hinzugefügt wird. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Erstellt und fügt ein Audio aus einem Byte-Array zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audioData | byte[] | Audio-Bytes. |

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio) - Hinzugefügtes Audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert Audios in das angegebene Array, beginnend am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbarer boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur lesbares Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ein java.util.Iterator für die gesamte Sammlung.