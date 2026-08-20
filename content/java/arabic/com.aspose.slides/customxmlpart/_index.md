---
title: CustomXmlPart
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل جزء XML مخصص.
type: docs
url: /ar/com.aspose.slides/customxmlpart/
---
**Inheritance:**
الوراثة:

java.lang.Object

**All Implemented Interfaces:**
جميع الواجهات المنفذة:
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

يمثل جزء XML مخصص.
## الطرق

| Method | Description |
| --- | --- |
| [getXmlData()](#getXmlData--) | يرجع أو يضبط بيانات XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returns or sets xml data. |
| [getXmlAsString()](#getXmlAsString--) | يرجع أو يضبط بيانات XML كسلسلة UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returns or sets xml data as UTF-8 string. |
| [getItemId()](#getItemId--) | يحدد معرفًا عالميًا فريدًا (GUID) يحدد بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | يرجع مجموعة مخططات XML المرتبطة بجزء XML المخصص. |
| [remove()](#remove--) | يزيل جزء XML المخصص من العرض التقديمي. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


يرجع أو يضبط بيانات XML. قابل للقراءة/الكتابة byte[].

**القيمة المرتجعة:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


يرجع أو يضبط بيانات XML. قابل للقراءة/الكتابة byte[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


يرجع أو يضبط بيانات XML كسلسلة UTF-8. قابل للقراءة/الكتابة String.

**القيمة المرتجعة:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


يرجع أو يضبط بيانات XML كسلسلة UTF-8. قابل للقراءة/الكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


يحدد معرفًا عالميًا فريدًا (GUID) يحدد بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. للقراءة فقط java.util.UUID.

**القيمة المرتجعة:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


يحدد معرفًا عالميًا فريدًا (GUID) يحدد بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. للقراءة فقط java.util.UUID.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


يرجع مجموعة مخططات XML المرتبطة بجزء XML المخصص. للقراءة فقط String[].

**القيمة المرتجعة:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


يزيل جزء XML المخصص من العرض التقديمي.