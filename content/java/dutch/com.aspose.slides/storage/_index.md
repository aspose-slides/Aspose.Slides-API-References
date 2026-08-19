---
title: Storage
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een tijdelijke gegevensopslag voor.
type: docs
url: /nl/com.aspose.slides/storage/
---
**Erfenis:**
java.lang.Object
```
public final class Storage
```

Stelt een tijdelijke gegevensopslag voor voor [WebDocument](../../com.aspose.slides/webdocument).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Storage()](#Storage--) |  |
## Methods

| Method | Beschrijving |
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


Puts the value into the storage.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Key for the value. |
| value | TValue | Value. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Gets the data from the storage.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
TValue - Gegevenswaarde indien aanwezig in de gegevensverzameling, null anders.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Determines whether the storage contains an element with the specified key.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
boolean - True als de opslag een element bevat met de opgegeven sleutel, false anders.