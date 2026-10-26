---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt aangepast xml-gedeelte.
type: docs
url: /nl/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Vertegenwoordigt aangepast xml-gedeelte.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Geeft xml-gegevens terug of stelt xml-gegevens in als UTF-8 String. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Geeft xml-gegevens terug of stelt xml-gegevens in als UTF-8 String. |
| [getXmlData()](#getXmlData--) | Geeft xml-gegevens terug of stelt xml-gegevens in. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Geeft xml-gegevens terug of stelt xml-gegevens in. |
| [getItemId()](#getItemId--) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Geeft de verzameling XML-schema's terug die aan het aangepaste XML-gedeelte zijn gekoppeld. |
| [remove()](#remove--) | Verwijdert het aangepaste xml-gedeelte uit de presentatie. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Geeft xml-gegevens terug of stelt xml-gegevens in als UTF-8 String. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Geeft xml-gegevens terug of stelt xml-gegevens in als UTF-8 String. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Geeft xml-gegevens terug of stelt xml-gegevens in. Lezen/Schrijven byte[].

**Retour:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Geeft xml-gegevens terug of stelt xml-gegevens in. Lezen/Schrijven byte[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-gedeelte binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Geeft de verzameling XML-schema's terug die aan het aangepaste XML-gedeelte zijn gekoppeld. Alleen-lezen String[].

**Retour:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert het aangepaste xml-gedeelte uit de presentatie.