---
title: Storage
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en tillfällig datalagring för .
type: docs
url: /sv/com.aspose.slides/storage/
---
**Arv:**
java.lang.Object
```
public final class Storage
```

Representerar en tillfällig datalagring för [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktörer

| Constructor | Beskrivning |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metoder

| Method | Beskrivning |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Lägger till värdet i lagringen. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Hämtar datan från lagringen. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bestämmer om lagringen innehåller ett element med den angivna nyckeln. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Lägger till värdet i lagringen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för värdet. |
| value | TValue | Värde. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Hämtar datan från lagringen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckeln för värdet. |

**Returnerar:**
TValue - Datavärde om det finns i datainsamlingen, null annars.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Bestämmer om lagringen innehåller ett element med den angivna nyckeln.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckeln för värdet. |

**Returnerar:**
boolean - Sant om lagringen innehåller ett element med den angivna nyckeln, falskt annars.