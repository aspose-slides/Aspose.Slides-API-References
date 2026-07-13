---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /pl/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Reprezentuje zamknięte napisy WebVTT.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Zwraca globalnie unikalny identyfikator (GUID) zamkniętych napisów. |
| [getLabel()](#getLabel--) | Zwraca lub ustawia etykietę zamkniętych napisów. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Zwraca lub ustawia etykietę zamkniętych napisów. |
| [getBinaryData()](#getBinaryData--) | Zwraca dane binarne zamkniętych napisów. |
| [getDataAsString()](#getDataAsString--) | Zwraca dane zamkniętych napisów jako ciąg znaków zakodowany w UTF-8. Tylko do odczytu String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Zwraca globalnie unikalny identyfikator (GUID) zamkniętych napisów. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Zwraca lub ustawia etykietę zamkniętych napisów. Do odczytu i zapisu String.

**Zwraca:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Zwraca lub ustawia etykietę zamkniętych napisów. Do odczytu i zapisu String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Zwraca dane binarne zamkniętych napisów. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Zwraca dane zamkniętych napisów jako ciąg znaków zakodowany w UTF-8. Tylko do odczytu String.

**Zwraca:**
java.lang.String