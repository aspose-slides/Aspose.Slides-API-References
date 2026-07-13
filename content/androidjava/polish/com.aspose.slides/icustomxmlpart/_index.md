---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /pl/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Reprezentuje niestandardową część XML.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Zwraca lub ustawia dane XML jako ciąg UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Zwraca lub ustawia dane XML jako ciąg UTF-8. |
| [getXmlData()](#getXmlData--) | Zwraca lub ustawia dane XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Zwraca lub ustawia dane XML. |
| [getItemId()](#getItemId--) | Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Zwraca zbiór schematów XML powiązanych z niestandardową częścią XML. |
| [remove()](#remove--) | Usuwa niestandardową część XML z prezentacji. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Zwraca lub ustawia dane XML jako ciąg UTF-8. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Zwraca lub ustawia dane XML jako ciąg UTF-8. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Zwraca lub ustawia dane XML. Odczyt/zapis byte[].

**Zwraca:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Zwraca lub ustawia dane XML. Odczyt/zapis byte[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Określa globalnie unikalny identyfikator (GUID), który jednoznacznie identyfikuje pojedynczą niestandardową część XML w dokumencie Office Open XML. Tylko do odczytu java.util.UUID.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Zwraca zbiór schematów XML powiązanych z niestandardową częścią XML. Tylko do odczytu String[].

**Zwraca:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Usuwa niestandardową część XML z prezentacji.