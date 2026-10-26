---
title: ICaptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar WebVTT-undertexter.
type: docs
url: /sv/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Representerar WebVTT-undertexter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returnerar den globalt unika identifieraren (GUID) för undertexterna. |
| [getLabel()](#getLabel--) | Returnerar eller ändrar etiketten för undertexterna. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returnerar eller ändrar etiketten för undertexterna. |
| [getBinaryData()](#getBinaryData--) | Returnerar den binära datan för undertexterna. |
| [getDataAsString()](#getDataAsString--) | Returnerar undertextdata som UTF-8-kodad sträng. Skrivskyddad String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Returnerar den globalt unika identifieraren (GUID) för undertexterna. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Returnerar eller ändrar etiketten för undertexterna. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Returnerar eller ändrar etiketten för undertexterna. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returnerar den binära datan för undertexterna. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Returnerar undertextdata som UTF-8-kodad sträng. Skrivskyddad String.

**Returnerar:**
java.lang.String