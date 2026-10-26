---
title: CustomXmlPart
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل جزء XML مخصص.
type: docs
url: /ar/com.aspose.slides/customxmlpart/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

يمثل جزء XML مخصص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getXmlData()](#getXmlData--) | تُرجع أو تُعيّن بيانات XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | تُرجع أو تُعيّن بيانات XML. |
| [getXmlAsString()](#getXmlAsString--) | تُرجع أو تُعيّن بيانات XML كـ String UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | تُرجع أو تُعيّن بيانات XML كـ String UTF-8. |
| [getItemId()](#getItemId--) | يُحدّد معرفًا فريدًا عالميًا (GUID) يُعرّف جزء XML مخصص واحد داخل مستند Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | يُحدّد معرفًا فريدًا عالميًا (GUID) يُعرّف جزء XML مخصص واحد داخل مستند Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | يُرجع مجموعة مخططات XML المرتبطة بالجزء XML المخصص. |
| [remove()](#remove--) | يزيل الجزء XML المخصص من العرض التقديمي. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


تُرجع أو تُعيّن بيانات XML. قراءة/كتابة byte[].

**الإرجاع:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


تُرجع أو تُعيّن بيانات XML. قراءة/كتابة byte[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


تُرجع أو تُعيّن بيانات XML كـ String UTF-8. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


تُرجع أو تُعيّن بيانات XML كـ String UTF-8. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


يُحدّد معرفًا فريدًا عالميًا (GUID) يُعرّف جزء XML مخصص واحد داخل مستند Office Open XML. للقراءة فقط java.util.UUID.

**الإرجاع:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


يُحدّد معرفًا فريدًا عالميًا (GUID) يُعرّف جزء XML مخصص واحد داخل مستند Office Open XML. للقراءة فقط java.util.UUID.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


يُرجع مجموعة مخططات XML المرتبطة بالجزء XML المخصص. للقراءة فقط String[].

**الإرجاع:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


يزيل الجزء XML المخصص من العرض التقديمي.