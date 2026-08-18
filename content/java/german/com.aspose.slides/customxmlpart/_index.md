---
title: CustomXmlPart
second_title: Aspose.Slides für Java API Referenz
description: Stellt ein benutzerdefiniertes XML-Teil dar.
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

Stellt ein benutzerdefiniertes XML-Teil dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXmlData()](#getXmlData--) | Gibt XML-Daten zurück oder setzt sie. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Gibt XML-Daten zurück oder setzt sie. |
| [getXmlAsString()](#getXmlAsString--) | Gibt XML-Daten als UTF-8-String zurück oder setzt sie. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Gibt XML-Daten als UTF-8-String zurück oder setzt sie. |
| [getItemId()](#getItemId--) | Gibt einen global eindeutig identifizierenden Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Gibt einen global eindeutig identifizierenden Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Gibt die Sammlung von XML-Schemata zurück, die dem benutzerdefinierten XML-Teil zugeordnet sind. |
| [remove()](#remove--) | Entfernt das benutzerdefinierte XML-Teil aus der Präsentation. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Gibt XML-Daten zurück oder setzt sie. Lesen/Schreiben byte[].

**Rückgabe:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Gibt XML-Daten zurück oder setzt sie. Lesen/Schreiben byte[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Gibt XML-Daten als UTF-8-String zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Gibt XML-Daten als UTF-8-String zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Gibt einen global eindeutig identifizierenden Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur lesbar java.util.UUID.

**Rückgabe:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Gibt einen global eindeutig identifizierenden Bezeichner (GUID) an, der ein einzelnes benutzerdefiniertes XML-Teil innerhalb eines Office Open XML-Dokuments eindeutig identifiziert. Nur lesbar java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Gibt die Sammlung von XML-Schemata zurück, die dem benutzerdefinierten XML-Teil zugeordnet sind. Nur lesbar String[].

**Rückgabe:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Entfernt das benutzerdefinierte XML-Teil aus der Präsentation.