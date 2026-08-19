---
title: Storage
second_title: Aspose.Slides för Java API-referens
description: Representerar en temporär datalagring för .
type: docs
url: /sv/com.aspose.slides/storage/
---
**Arv:**
java.lang.Object
```
public final class Storage
```

Representerar en temporär datalagring för [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Lagrar värdet i lagringen. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Hämtar data från lagringen. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Avgör om lagringen innehåller ett element med den angivna nyckeln. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Lagrar värdet i lagringen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för värdet. |
| value | TValue | Värde. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Hämtar data från lagringen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för värdet. |

**Returnerar:**
TValue - Datavärde om det finns i datainsamlingen, annars null.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Avgör om lagringen innehåller ett element med den angivna nyckeln.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för värdet. |

**Returnerar:**
boolean - Sant om lagringen innehåller ett element med den angivna nyckeln, falskt annars.