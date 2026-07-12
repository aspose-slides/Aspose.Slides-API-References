---
title: ICustomXmlPart
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt ein benutzerdefiniertes XML-Teil dar.
type: docs
url: /de/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Stellt ein benutzerdefiniertes XML-Teil dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Liefert oder setzt XML-Daten als UTF-8-Zeichenfolge. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Liefert oder setzt XML-Daten als UTF-8-Zeichenfolge. |
| [getXmlData()](#getXmlData--) | Liefert oder setzt XML-Daten. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Liefert oder setzt XML-Daten. |
| [getItemId()](#getItemId--) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Liefert die Sammlung von XML-Schemata, die dem benutzerdefinierten XML-Teil zugeordnet sind. |
| [remove()](#remove--) | Entfernt das benutzerdefinierte XML-Teil aus der Präsentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Liefert oder setzt XML-Daten als UTF-8-Zeichenfolge. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Liefert oder setzt XML-Daten als UTF-8-Zeichenfolge. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Liefert oder setzt XML-Daten. Lese/Schreib byte[].

**Rückgabe:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Liefert oder setzt XML-Daten. Lese/Schreib byte[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur-Lese java.util.UUID.

**Rückgabe:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur-Lese java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Liefert die Sammlung von XML-Schemata, die dem benutzerdefinierten XML-Teil zugeordnet sind. Nur-Lese String[].

**Rückgabe:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt das benutzerdefinierte XML-Teil aus der Präsentation.