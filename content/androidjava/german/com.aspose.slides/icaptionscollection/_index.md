---
title: ICaptionsCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung der geschlossenen Untertitel dar.
type: docs
url: /de/com.aspose.slides/icaptionscollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Stellt eine Sammlung der geschlossenen Untertitel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die geschlossenen Untertitel am angegebenen Index zurück. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung WebVTT-Untertitel am Ende hinzu. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Fügt der Sammlung WebVTT-Untertitel vom Stream am Ende hinzu. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Entfernt die angegebenen geschlossenen Untertitel aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die geschlossenen Untertitel am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle geschlossenen Untertitel aus der Sammlung. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Gibt die geschlossenen Untertitel am angegebenen Index zurück. Nur lesbar [ICaptions](../../com.aspose.slides/icaptions).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Fügt der Sammlung WebVTT-Untertitel am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | java.lang.String | Die Bezeichnung der geschlossenen Untertitel. |
| filePath | java.lang.String | Der Pfad zur WebVTT-Datei. |

**Rückgabewert:**
[ICaptions](../../com.aspose.slides/icaptions) - Die hinzugefügte [ICaptions](../../com.aspose.slides/icaptions) Instanz.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Fügt der Sammlung WebVTT-Untertitel vom Stream am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | java.lang.String | Die Bezeichnung der geschlossenen Untertitel. |
| stream | java.io.InputStream | Der Eingabestream, der Daten im WebVTT-Format enthält. |

**Rückgabewert:**
[ICaptions](../../com.aspose.slides/icaptions) - Die hinzugefügte [ICaptions](../../com.aspose.slides/icaptions) Instanz.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Entfernt die angegebenen geschlossenen Untertitel aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Die zu entfernenden geschlossenen Untertitel. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt die geschlossenen Untertitel am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index der zu entfernenden geschlossenen Untertitel. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle geschlossenen Untertitel aus der Sammlung.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbar  int .

**Rückgabewert:**
int