---
title: Captions
second_title: Aspose.Slides för Java API-referens
description: Representerar de stängda WebVTT-undertexterna.
type: docs
url: /sv/com.aspose.slides/captions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Representerar WebVTT-undertexter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returnerar den globalt unika identifieraren (GUID) för undertexterna. |
| [getLabel()](#getLabel--) | Returnerar eller sätter etiketten för undertexterna. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returnerar eller sätter etiketten för undertexterna. |
| [getBinaryData()](#getBinaryData--) | Returnerar de binära data för undertexterna. |
| [getDataAsString()](#getDataAsString--) | Returnerar undertextdata som UTF-8-kodad sträng. Skrivskyddad String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Returnerar den globalt unika identifieraren (GUID) för undertexterna. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Returnerar eller sätter etiketten för undertexterna. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Returnerar eller sätter etiketten för undertexterna. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returnerar de binära data för undertexterna. Skrivskyddad byte[] .

**Returnerar:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Returnerar undertextdata som UTF-8-kodad sträng. Skrivskyddad String.

**Returnerar:**
java.lang.String