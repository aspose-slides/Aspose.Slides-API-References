---
title: Storage
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een tijdelijke gegevensopslag voor .
type: docs
url: /nl/com.aspose.slides/storage/
---
**Erfenis:**
java.lang.Object
```
public final class Storage
```

Vertegenwoordigt een tijdelijke gegevensopslag voor [WebDocument](../../com.aspose.slides/webdocument).
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Storage()](#Storage--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Puts the value into the storage. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Gets the data from the storage. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the storage contains an element with the specified key. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Plaatst de waarde in de opslag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel voor de waarde. |
| value | TValue | Waarde. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Haalt de gegevens uit de opslag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel van de waarde. |

**Returns:**
TValue - Gegevenswaarde als deze aanwezig is in de gegevenscollectie, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Bepaalt of de opslag een element bevat met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel van de waarde. |

**Returns:**
boolean - True if the storage contains an element with the specified key, false otherwise.