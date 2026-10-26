---
title: ICaptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die WebVTT-Untertitel dar.
type: docs
url: /de/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Stellt die WebVTT-Untertitel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returns the globally unique identifier (GUID) of the closed captions. |
| [getLabel()](#getLabel--) | Returns or sets the label of the closed captions. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returns or sets the label of the closed captions. |
| [getBinaryData()](#getBinaryData--) | Returns the binary data of the closed captions. |
| [getDataAsString()](#getDataAsString--) | Returns the closed captions data as UTF-8 encoded string Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Gibt die global eindeutige Kennung (GUID) der Untertitel zurück. Nur lesend java.util.UUID.

**Rückgabe:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Gibt das Label der Untertitel zurück oder setzt es. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Gibt das Label der Untertitel zurück oder setzt es. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Gibt die Binärdaten der Untertitel zurück. Nur lesend byte[].

**Rückgabe:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Gibt die Untertitel-Daten als UTF-8-kodierten String zurück. Nur lesend String.

**Rückgabe:**
java.lang.String