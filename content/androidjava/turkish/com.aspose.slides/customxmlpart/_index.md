---
title: CustomXmlPart
second_title: Java API Referansı ile Android için Aspose.Slides
description: Özel xml bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/customxmlpart/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Özel xml bölümünü temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getXmlData()](#getXmlData--) | XML verisini döndürür veya ayarlar. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | XML verisini döndürür veya ayarlar. |
| [getXmlAsString()](#getXmlAsString--) | XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. |
| [getItemId()](#getItemId--) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. |
| [remove()](#remove--) | Özel xml bölümünü sunumdan kaldırır. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

XML verisini döndürür veya ayarlar. Okunur/yazılır byte[].

**Döndürür:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

XML verisini döndürür veya ayarlar. Okunur/yazılır byte[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

XML verisini UTF-8 dizesi olarak döndürür veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. Salt-okunur java.util.UUID.

**Döndürür:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Office Open XML belgesi içinde tek bir özel XML bölümünü benzersiz şekilde tanımlayan küresel olarak benzersiz bir tanımlayıcıyı (GUID) belirtir. Salt-okunur java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Özel XML bölümüyle ilişkili XML şema koleksiyonunu döndürür. Salt-okunur String[].

**Döndürür:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Özel xml bölümünü sunumdan kaldırır.