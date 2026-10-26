---
title: Storage
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen temporären Datenspeicher für .
type: docs
url: /de/com.aspose.slides/storage/
---
**Vererbung:**
java.lang.Object
```
public final class Storage
```

Stellt einen temporären Datenspeicher für [WebDocument](../../com.aspose.slides/webdocument) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Storage()](#Storage--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Fügt den Wert in den Speicher ein. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Liest die Daten aus dem Speicher. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Schlüssel für den Wert. |
| value | TValue | Wert. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

Liest die Daten aus dem Speicher.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Schlüssel des Wertes. |

**Rückgabewert:**
TValue - Datenwert, wenn er in der Datensammlung vorhanden ist, null andernfalls.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

Bestimmt, ob der Speicher ein Element mit dem angegebenen Schlüssel enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Schlüssel des Wertes. |

**Rückgabewert:**
boolean - True wenn der Speicher ein Element mit dem angegebenen Schlüssel enthält, false andernfalls.