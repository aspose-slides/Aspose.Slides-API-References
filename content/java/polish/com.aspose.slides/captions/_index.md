---
title: Captions
second_title: Aspose.Slides dla Java – odwołanie API
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

Reprezentuje napisy zamknięte WebVTT.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Zwraca globalny unikatowy identyfikator (GUID) napisów zamkniętych. |
| [getLabel()](#getLabel--) | Zwraca lub ustawia etykietę napisów zamkniętych. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Zwraca lub ustawia etykietę napisów zamkniętych. |
| [getBinaryData()](#getBinaryData--) | Zwraca dane binarne napisów zamkniętych. |
| [getDataAsString()](#getDataAsString--) | Zwraca dane napisów zamkniętych jako ciąg znaków zakodowany UTF-8. Tylko do odczytu String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Zwraca globalny unikatowy identyfikator (GUID) napisów zamkniętych. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Zwraca lub ustawia etykietę napisów zamkniętych. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Zwraca lub ustawia etykietę napisów zamkniętych. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Zwraca dane binarne napisów zamkniętych. Tylko do odczytu byte[] .

**Zwraca:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Zwraca dane napisów zamkniętych jako ciąg znaków zakodowany UTF-8. Tylko do odczytu String.

**Zwraca:**
java.lang.String