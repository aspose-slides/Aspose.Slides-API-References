---
title: Storage
second_title: Aspose.Slides for Java API Reference
description:  Represents a temporary data storage for .
type: docs
weight: 526
url: /java/com.aspose.slides/storage/
---
**Inheritance:**
java.lang.Object
```
public final class Storage
```

Represents a temporary data storage for [WebDocument](../../com.aspose.slides/webdocument).
## Constructors

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## Methods

| Method | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key for the value. |
| value | TValue | Value. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Gets the data from the storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
TValue - Data value if it is presented in the data collection, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Determines whether the storage contains an element with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
boolean - True if the storage contains an element with the specified key, false otherwise.
