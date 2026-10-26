---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Özel xml bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Özel xml bölümünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. |
| [getXmlData()](#getXmlData--) | XML verisini döndürür veya ayarlar. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML verisini döndürür veya ayarlar. |
| [getItemId()](#getItemId--) | Tek bir özel XML bölümünü Office Open XML belgesi içinde benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Tek bir özel XML bölümünü Office Open XML belgesi içinde benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. |
| [remove()](#remove--) | Özel xml bölümünü sunumdan kaldırır. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


XML verisini döndürür veya ayarlar. Okuma/yazma byte[].

**Döndürür:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


XML verisini döndürür veya ayarlar. Okuma/yazma byte[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


Tek bir özel XML bölümünü Office Open XML belgesi içinde benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. Sadece okunabilir java.util.UUID.

**Döndürür:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


Tek bir özel XML bölümünü Office Open XML belgesi içinde benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. Sadece okunabilir java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. Sadece okunabilir String[].

**Döndürür:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


Özel xml bölümünü sunumdan kaldırır.