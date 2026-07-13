---
title: CustomXmlPart
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje niestandardową część XML.
type: docs
url: /pl/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Reprezentuje niestandardową część XML.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXmlData()](#getXmlData--) | Zwraca lub ustawia dane XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Zwraca lub ustawia dane XML. |
| [getXmlAsString()](#getXmlAsString--) | Zwraca lub ustawia dane XML jako ciąg UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Zwraca lub ustawia dane XML jako ciąg UTF-8. |
| [getItemId()](#getItemId--) | Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Zwraca kolekcję schematów XML powiązanych z niestandardową częścią XML. |
| [remove()](#remove--) | Usuwa niestandardową część XML z prezentacji. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Zwraca lub ustawia dane XML. Odczyt/zapis byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Zwraca lub ustawia dane XML. Odczyt/zapis byte[].

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Zwraca lub ustawia dane XML jako ciąg UTF-8. Odczyt/zapis String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Zwraca lub ustawia dane XML jako ciąg UTF-8. Odczyt/zapis String.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. Tylko do odczytu java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. Tylko do odczytu java.util.UUID.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Zwraca kolekcję schematów XML powiązanych z niestandardową częścią XML. Tylko do odczytu String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Usuwa niestandardową część XML z prezentacji.