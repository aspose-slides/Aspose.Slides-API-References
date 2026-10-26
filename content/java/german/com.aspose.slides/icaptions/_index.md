---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
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
| [getCaptionId()](#getCaptionId--) | Gibt die global eindeutige Kennung (GUID) der Untertitel zurück. |
| [getLabel()](#getLabel--) | Gibt die Bezeichnung der Untertitel zurück oder legt sie fest. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Gibt die Bezeichnung der Untertitel zurück oder legt sie fest. |
| [getBinaryData()](#getBinaryData--) | Gibt die Binärdaten der Untertitel zurück. |
| [getDataAsString()](#getDataAsString--) | Gibt die Untertitel-Daten als UTF-8-kodierten String zurück. Nur-Lese-String. |

### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Gibt die global eindeutige Kennung (GUID) der Untertitel zurück. Nur-Lese-java.util.UUID.

**Rückgabewert:**
java.util.UUID

### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Gibt die Bezeichnung der Untertitel zurück oder legt sie fest. Lese-/Schreib-String.

**Rückgabewert:**
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Gibt die Bezeichnung der Untertitel zurück oder legt sie fest. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Gibt die Binärdaten der Untertitel zurück. Nur-Lese-byte[].

**Rückgabewert:**
byte[]

### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Gibt die Untertitel-Daten als UTF-8-kodierten String zurück. Nur-Lese-String.

**Rückgabewert:**
java.lang.String