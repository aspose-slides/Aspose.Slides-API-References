---
title: CustomXmlPart
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje vlastní XML část.
type: docs
url: /cs/com.aspose.slides/customxmlpart/
---
**Dědění:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Reprezentuje vlastní XML část.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXmlData()](#getXmlData--) | Vrací nebo nastavuje XML data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Vrací nebo nastavuje XML data. |
| [getXmlAsString()](#getXmlAsString--) | Vrací nebo nastavuje XML data jako řetězec UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Vrací nebo nastavuje XML data jako řetězec UTF-8. |
| [getItemId()](#getItemId--) | Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jednu vlastní XML část v dokumentu Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jednu vlastní XML část v dokumentu Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Vrací kolekci schémat XML, která jsou spojena s vlastní XML částí. |
| [remove()](#remove--) | Odstraňuje vlastní XML část z prezentace. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Vrací nebo nastavuje XML data. Čtení/zápis byte[].

**Vrací:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Vrací nebo nastavuje XML data. Čtení/zápis byte[].

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Vrací nebo nastavuje XML data jako řetězec UTF-8. Čtení/zápis String.

**Vrací:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Vrací nebo nastavuje XML data jako řetězec UTF-8. Čtení/zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jednu vlastní XML část v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Určuje globálně jedinečný identifikátor (GUID), který jednoznačně identifikuje jednu vlastní XML část v dokumentu Office Open XML. Pouze pro čtení java.util.UUID.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Vrací kolekci schémat XML, která jsou spojena s vlastní XML částí. Pouze pro čtení String[].

**Vrací:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Odstraňuje vlastní XML část z prezentace.