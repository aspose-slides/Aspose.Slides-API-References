---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Representerar de stängda undertexterna i WebVTT.
type: docs
url: /sv/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Representerar de stängda undertexterna i WebVTT.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returnerar den globalt unika identifieraren (GUID) för de stängda undertexterna. |
| [getLabel()](#getLabel--) | Returnerar eller anger etiketten för de stängda undertexterna. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returnerar eller anger etiketten för de stängda undertexterna. |
| [getBinaryData()](#getBinaryData--) | Returnerar den binära datan för de stängda undertexterna. |
| [getDataAsString()](#getDataAsString--) | Returnerar de stängda undertexternas data som en UTF-8-kodad sträng Skrivskyddad String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Returnerar den globalt unika identifieraren (GUID) för de stängda undertexterna. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Returnerar eller anger etiketten för de stängda undertexterna. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Returnerar eller anger etiketten för de stängda undertexterna. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returnerar den binära datan för de stängda undertexterna. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Returnerar de stängda undertexternas data som en UTF-8-kodad sträng Skrivskyddad String.

**Returnerar:**
java.lang.String