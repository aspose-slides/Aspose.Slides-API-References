---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Stellt einen benutzerdefinierten XML-Teil dar.
type: docs
url: /de/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Stellt einen benutzerdefinierten XML-Teil dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Gibt XML-Daten als UTF-8-String zurück oder legt sie fest. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Gibt XML-Daten als UTF-8-String zurück oder legt sie fest. |
| [getXmlData()](#getXmlData--) | Gibt XML-Daten zurück oder legt sie fest. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Gibt XML-Daten zurück oder legt sie fest. |
| [getItemId()](#getItemId--) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Gibt die Sammlung von XML-Schemas zurück, die dem benutzerdefinierten XML-Teil zugeordnet sind. |
| [remove()](#remove--) | Entfernt den benutzerdefinierten XML-Teil aus der Präsentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Gibt XML-Daten als UTF-8-String zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Gibt XML-Daten als UTF-8-String zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Gibt XML-Daten zurück oder legt sie fest. Lesen/Schreiben byte[].

**Rückgabewert:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Gibt XML-Daten zurück oder legt sie fest. Lesen/Schreiben byte[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur lesend java.util.UUID.

**Rückgabewert:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur lesend java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Gibt die Sammlung von XML-Schemas zurück, die dem benutzerdefinierten XML-Teil zugeordnet sind. Nur lesend String[].

**Rückgabewert:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den benutzerdefinierten XML-Teil aus der Präsentation.