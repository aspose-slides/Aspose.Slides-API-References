---
title: CustomXmlPart
second_title: Aspose.Slides for Java API Referansı
description: Özel XML bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Özel XML bölümünü temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getXmlData()](#getXmlData--) | XML verisini alır veya ayarlar. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML verisini alır veya ayarlar. |
| [getXmlAsString()](#getXmlAsString--) | XML verisini UTF-8 dizesi olarak alır veya ayarlar. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML verisini UTF-8 dizesi olarak alır veya ayarlar. |
| [getItemId()](#getItemId--) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. |
| [remove()](#remove--) | Özel XML bölümünü sunumdan kaldırır. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


XML verisini alır veya ayarlar. Okuma/yazma byte[].

**Döndürür:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


XML verisini alır veya ayarlar. Okuma/yazma byte[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


XML verisini UTF-8 dizesi olarak alır veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


XML verisini UTF-8 dizesi olarak alır veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. Yalnızca okuma java.util.UUID.

**Döndürür:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel benzersiz tanımlayıcıyı (GUID) belirtir. Yalnızca okuma java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. Yalnızca okuma String[].

**Döndürür:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Özel XML bölümünü sunumdan kaldırır.