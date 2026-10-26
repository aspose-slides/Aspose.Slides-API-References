---
title: CustomXmlPart
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een aangepast xml-onderdeel voor.
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

Stelt een aangepast xml-onderdeel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXmlData()](#getXmlData--) | Retourneert of stelt xml-gegevens in. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Retourneert of stelt xml-gegevens in. |
| [getXmlAsString()](#getXmlAsString--) | Retourneert of stelt xml-gegevens in als UTF-8-string. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Retourneert of stelt xml-gegevens in als UTF-8-string. |
| [getItemId()](#getItemId--) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Retourneert de collectie XML-schema's die geassocieerd zijn met het aangepaste XML-onderdeel. |
| [remove()](#remove--) | Verwijdert het aangepaste xml-onderdeel uit de presentatie. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Retourneert of stelt xml-gegevens in. Lezen/schrijven byte[].

**Retour:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Retourneert of stelt xml-gegevens in. Lezen/schrijven byte[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Retourneert of stelt xml-gegevens in als UTF-8-string. Lezen/schrijven String.

**Retour:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Retourneert of stelt xml-gegevens in als UTF-8-string. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Specificeert een wereldwijd unieke identifier (GUID) die een enkel aangepast XML-onderdeel binnen een Office Open XML-document uniek identificeert. Alleen-lezen java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Retourneert de collectie XML-schema's die geassocieerd zijn met het aangepaste XML-onderdeel. Alleen-lezen String[].

**Retour:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Verwijdert het aangepaste xml-onderdeel uit de presentatie.