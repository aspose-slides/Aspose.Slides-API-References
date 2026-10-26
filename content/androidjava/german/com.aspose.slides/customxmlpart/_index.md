---
title: CustomXmlPart
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt ein benutzerdefiniertes xml-Teil dar.
type: docs
url: /de/com.aspose.slides/customxmlpart/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Stellt ein benutzerdefiniertes xml-Teil dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmlData()](#getXmlData--) | Liefert oder setzt xml-Daten. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Liefert oder setzt xml-Daten. |
| [getXmlAsString()](#getXmlAsString--) | Liefert oder setzt xml-Daten als UTF-8-Zeichenkette. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Liefert oder setzt xml-Daten als UTF-8-Zeichenkette. |
| [getItemId()](#getItemId--) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Liefert die Sammlung von XML-Schemas, die mit dem benutzerdefinierten XML-Teil verknüpft sind. |
| [remove()](#remove--) | Entfernt das benutzerdefinierte xml-Teil aus der Präsentation. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Liefert oder setzt xml-Daten. Lesen/Schreiben byte[].

**Rückgabe:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Liefert oder setzt xml-Daten. Lesen/Schreiben byte[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Liefert oder setzt xml-Daten als UTF-8-Zeichenkette. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Liefert oder setzt xml-Daten als UTF-8-Zeichenkette. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur-Lesen java.util.UUID.

**Rückgabe:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Gibt einen global eindeutigen Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur-Lesen java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Liefert die Sammlung von XML-Schemas, die mit dem benutzerdefinierten XML-Teil verknüpft sind. Nur-Lesen String[].

**Rückgabe:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Entfernt das benutzerdefinierte xml-Teil aus der Präsentation.