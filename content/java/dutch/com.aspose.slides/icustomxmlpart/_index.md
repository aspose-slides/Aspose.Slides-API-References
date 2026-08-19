---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Stelt een aangepast xml-onderdeel voor.
type: docs
url: /nl/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Stelt een aangepast xml-onderdeel voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Geeft xml-gegevens terug of stelt ze in als UTF-8 string. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Geeft xml-gegevens terug of stelt ze in als UTF-8 string. |
| [getXmlData()](#getXmlData--) | Geeft xml-gegevens terug of stelt ze in. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Geeft xml-gegevens terug of stelt ze in. |
| [getItemId()](#getItemId--) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Geeft de verzameling XML-schema's terug die geassocieerd zijn met het aangepaste XML-onderdeel. |
| [remove()](#remove--) | Verwijdert het aangepaste xml-onderdeel uit de presentatie. |

### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Geeft xml-gegevens terug of stelt ze in als UTF-8 string. Lezen/schrijven String.

**Retour:**
java.lang.String

### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Geeft xml-gegevens terug of stelt ze in als UTF-8 string. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Geeft xml-gegevens terug of stelt ze in. Lezen/schrijven byte[].

**Retour:**
byte[]

### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Geeft xml-gegevens terug of stelt ze in. Lezen/schrijven byte[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID

### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Geeft de verzameling XML-schema's terug die geassocieerd zijn met het aangepaste XML-onderdeel. Alleen-lezen String[].

**Retour:**
java.lang.String[]

### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert het aangepaste xml-onderdeel uit de presentatie.