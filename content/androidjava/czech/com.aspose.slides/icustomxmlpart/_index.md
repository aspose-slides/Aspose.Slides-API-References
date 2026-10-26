---
title: ICustomXmlPart
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje vlastní XML část.
type: docs
url: /cs/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Reprezentuje vlastní XML část.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Vrací nebo nastavuje data XML jako řetězec UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Vrací nebo nastavuje data XML jako řetězec UTF-8. |
| [getXmlData()](#getXmlData--) | Vrací nebo nastavuje data XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Vrací nebo nastavuje data XML. |
| [getItemId()](#getItemId--) | Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní XML část v dokumentu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní XML část v dokumentu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Vrací kolekci XML schémat, která jsou spojena s vlastní XML částí. |
| [remove()](#remove--) | Odstraňuje vlastní XML část z prezentace. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Vrací nebo nastavuje data XML jako řetězec UTF-8. Číst/Zapisovat String.

**Vrací:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Vrací nebo nastavuje data XML jako řetězec UTF-8. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Vrací nebo nastavuje data XML. Číst/Zapisovat byte[].

**Vrací:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Vrací nebo nastavuje data XML. Číst/Zapisovat byte[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní XML část v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jedinou vlastní XML část v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Vrací kolekci XML schémat, která jsou spojena s vlastní XML částí. Pouze pro čtení String[].

**Vrací:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Odstraňuje vlastní XML část z prezentace.