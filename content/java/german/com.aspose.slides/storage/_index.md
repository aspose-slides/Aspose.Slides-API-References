---
title: Storage
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen temporären Datenspeicher für . dar.
type: docs
url: /de/com.aspose.slides/storage/
---
**Vererbung:**
java.lang.Object
```
public final class Storage
```

Repräsentiert einen temporären Datenspeicher für [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Storage()](#Storage--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Fügt den Wert in den Speicher ein. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Ruft die Daten aus dem Speicher ab. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bestimmt, ob der Speicher ein Element mit dem angegebenen Schlüssel enthält. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Fügt den Wert in den Speicher ein.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Schlüssel für den Wert. |
| value | TValue | Wert. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Ruft die Daten aus dem Speicher ab.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Schlüssel des Werts. |

**Rückgabewert:**
TValue - Datenwert, wenn er in der Datensammlung vorhanden ist, null sonst.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Bestimmt, ob der Speicher ein Element mit dem angegebenen Schlüssel enthält.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Schlüssel des Werts. |

**Rückgabewert:**
boolean - true, wenn der Speicher ein Element mit dem angegebenen Schlüssel enthält, false sonst.