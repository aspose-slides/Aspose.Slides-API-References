---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /tr/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Özel xml bölümünü temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | XML verilerini UTF-8 dizesi olarak alır veya ayarlar. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML verilerini UTF-8 dizesi olarak alır veya ayarlar. |
| [getXmlData()](#getXmlData--) | XML verilerini alır veya ayarlar. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML verilerini alır veya ayarlar. |
| [getItemId()](#getItemId--) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. |
| [remove()](#remove--) | Özel xml bölümünü sunumdan kaldırır. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

XML verilerini UTF-8 dizesi olarak alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

XML verilerini UTF-8 dizesi olarak alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

XML verilerini alır veya ayarlar. Okuma/Yazma byte[].

**Döndürür:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

XML verilerini alır veya ayarlar. Okuma/Yazma byte[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. Yalnızca okuma java.util.UUID.

**Döndürür:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. Yalnızca okuma java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. Yalnızca okuma String[].

**Döndürür:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Özel xml bölümünü sunumdan kaldırır.