---
title: CaptionsCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Untertiteln dar.
type: docs
url: /de/com.aspose.slides/captionscollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Stellt eine Sammlung von Untertiteln dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Untertitel am angegebenen Index zurück. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung WebVTT-Untertitel am Ende hinzu. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Fügt der Sammlung WebVTT-Untertitel am Ende aus einem Stream hinzu. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Entfernt die angegebenen Untertitel aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Untertitel am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Untertitel aus der Sammlung. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Gibt die Untertitel am angegebenen Index zurück. Nur lesbar [ICaptions](../../com.aspose.slides/icaptions).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Fügt der Sammlung WebVTT-Untertitel am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | java.lang.String | Die Bezeichnung der Untertitel. |
| filePath | java.lang.String | Der Pfad zur WebVTT-Datei. |

**Rückgabe:**
[ICaptions](../../com.aspose.slides/icaptions) - Die hinzugefügte [ICaptions](../../com.aspose.slides/icaptions) Instanz.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Fügt der Sammlung WebVTT-Untertitel am Ende aus einem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | java.lang.String | Die Bezeichnung der Untertitel. |
| stream | java.io.InputStream | Der Eingabestream, der Daten im WebVTT-Format enthält. |

**Rückgabe:**
[ICaptions](../../com.aspose.slides/icaptions) - Die hinzugefügte [ICaptions](../../com.aspose.slides/icaptions) Instanz.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Entfernt die angegebenen Untertitel aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Die zu entfernenden Untertitel. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt die Untertitel am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index der zu entfernenden Untertitel. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Untertitel aus der Sammlung.

### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbar int .

**Rückgabe:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Ein  System.Collections.Generic.IEnumerator1  der verwendet werden kann, um die Sammlung zu durchlaufen.