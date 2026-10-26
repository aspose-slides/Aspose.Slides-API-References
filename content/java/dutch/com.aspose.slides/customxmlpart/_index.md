---
title: CustomXmlPart
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een aangepast xml-gedeelte voor.
type: docs
url: /nl/com.aspose.slides/customxmlpart/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Stelt een aangepast xml-gedeelte voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXmlData()](#getXmlData--) | Geeft xml-gegevens terug of stelt deze in. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Geeft xml-gegevens terug of stelt deze in. |
| [getXmlAsString()](#getXmlAsString--) | Geeft xml-gegevens terug of stelt deze in als UTF-8-tekenreeks. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Geeft xml-gegevens terug of stelt deze in als UTF-8-tekenreeks. |
| [getItemId()](#getItemId--) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Geeft de verzameling XML-schema's terug die zijn gekoppeld aan het aangepaste XML-gedeelte. |
| [remove()](#remove--) | Verwijdert het aangepaste xml-gedeelte uit de presentatie. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Geeft xml-gegevens terug of stelt deze in. Lezen/Schrijven byte[].

**Retour:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Geeft xml-gegevens terug of stelt deze in. Lezen/Schrijven byte[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Geeft xml-gegevens terug of stelt deze in als UTF-8-tekenreeks. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Geeft xml-gegevens terug of stelt deze in als UTF-8-tekenreeks. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Geeft de verzameling XML-schema's terug die zijn gekoppeld aan het aangepaste XML-gedeelte. Alleen-lezen String[].

**Retour:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Verwijdert het aangepšte xml-gedeelte uit de presentatie.