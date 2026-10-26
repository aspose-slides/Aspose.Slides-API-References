---
title: Captions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt die WebVTT-Untertitel dar.
type: docs
url: /de/com.aspose.slides/captions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Stellt die WebVTT-Untertitel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Gibt die global eindeutige Kennung (GUID) der Untertitel zurück. |
| [getLabel()](#getLabel--) | Gibt das Etikett der Untertitel zurück oder setzt es. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Gibt das Etikett der Untertitel zurück oder setzt es. |
| [getBinaryData()](#getBinaryData--) | Gibt die Binärdaten der Untertitel zurück. |
| [getDataAsString()](#getDataAsString--) | Gibt die Untertitel-Daten als UTF-8-codierten String zurück. Nur-Lesen String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Gibt die global eindeutige Kennung (GUID) der Untertitel zurück. Nur-Lesen java.util.UUID.

**Rückgabe:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Gibt das Etikett der Untertitel zurück oder setzt es. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Gibt das Etikett der Untertitel zurück oder setzt es. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Gibt die Binärdaten der Untertitel zurück. Nur-Lesen byte[] .

**Rückgabe:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Gibt die Untertitel-Daten als UTF-8-codierten String zurück. Nur-Lesen String.

**Rückgabe:**
java.lang.String