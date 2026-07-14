---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /ar/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

يمثل جزء XML مخصص.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | إرجاع أو تعيين بيانات XML كسلسلة UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | إرجاع أو تعيين بيانات XML كسلسلة UTF-8. |
| [getXmlData()](#getXmlData--) | إرجاع أو تعيين بيانات XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | إرجاع أو تعيين بيانات XML. |
| [getItemId()](#getItemId--) | يحدد معرفًا فريدًا عالميًا (GUID) يعرّف بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | يحدد معرفًا فريدًا عالميًا (GUID) يعرّف بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | إرجاع مجموعة مخططات XML المرتبطة بجزء XML المخصص. |
| [remove()](#remove--) | يزيل جزء XML المخصص من العرض التقديمي. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

إرجاع أو تعيين بيانات XML كسلسلة UTF-8. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

إرجاع أو تعيين بيانات XML كسلسلة UTF-8. قراءة/كتابة String.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

إرجاع أو تعيين بيانات XML. قراءة/كتابة byte[].

**الإرجاع:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

إرجاع أو تعيين بيانات XML. قراءة/كتابة byte[].

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

يحدد معرفًا فريدًا عالميًا (GUID) يعرّف بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. قراءة فقط java.util.UUID.

**الإرجاع:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

يحدد معرفًا فريدًا عالميًا (GUID) يعرّف بشكل فريد جزء XML مخصص واحد داخل مستند Office Open XML. قراءة فقط java.util.UUID.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

إرجاع مجموعة مخططات XML المرتبطة بجزء XML المخصص. قراءة فقط String[].

**الإرجاع:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

يزيل جزء XML المخصص من العرض التقديمي.