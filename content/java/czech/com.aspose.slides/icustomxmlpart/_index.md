---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje vlastní část XML.
type: docs
url: /cs/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Reprezentuje vlastní část XML.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Vrací nebo nastavuje XML data jako řetězec UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Vrací nebo nastavuje XML data jako řetězec UTF-8. |
| [getXmlData()](#getXmlData--) | Vrací nebo nastavuje XML data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Vrací nebo nastavuje XML data. |
| [getItemId()](#getItemId--) | Specifikuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní část XML v dokumentu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifikuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní část XML v dokumentu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Vrací kolekci schémat XML, která jsou spojena s vlastní částí XML. |
| [remove()](#remove--) | Odstraňuje vlastní část XML z prezentace. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Vrací nebo nastavuje XML data jako řetězec UTF-8. Čtení/zápis String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Vrací nebo nastavuje XML data jako řetězec UTF-8. Čtení/zápis String.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Vrací nebo nastavuje XML data. Čtení/zápis byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Vrací nebo nastavuje XML data. Čtení/zápis byte[].

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Specifikuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní část XML v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Specifikuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní část XML v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Vrací kolekci schémat XML, která jsou spojena s vlastní částí XML. Pouze pro čtení String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Odstraňuje vlastní část XML z prezentace.