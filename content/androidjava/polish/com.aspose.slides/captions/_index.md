---
title: Captions
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje zamknięte napisy WebVTT.
type: docs
url: /pl/com.aspose.slides/captions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Reprezentuje zamknięte napisy WebVTT.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Zwraca globalnie unikalny identyfikator (GUID) zamkniętych napisów. |
| [getLabel()](#getLabel--) | Zwraca lub ustawia etykietę zamkniętych napisów. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Zwraca lub ustawia etykietę zamkniętych napisów. |
| [getBinaryData()](#getBinaryData--) | Zwraca dane binarne zamkniętych napisów. |
| [getDataAsString()](#getDataAsString--) | Zwraca dane zamkniętych napisów jako ciąg znaków zakodowany w UTF-8 Tylko do odczytu String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

Zwraca globalnie unikalny identyfikator (GUID) zamkniętych napisów. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

Zwraca lub ustawia etykietę zamkniętych napisów. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

Zwraca lub ustawia etykietę zamkniętych napisów. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Zwraca dane binarne zamkniętych napisów. Tylko do odczytu  byte[] .

**Zwraca:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

Zwraca dane zamkniętych napisów jako ciąg znaków zakodowany w UTF-8 Tylko do odczytu String.

**Zwraca:**
java.lang.String