---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: يمثل جزء XML مخصص.
type: docs
url: /ar/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

يمثل جزء XML مخصص.
## الدوال

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | إرجاع أو تعيين بيانات xml كسلسلة UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | إرجاع أو تعيين بيانات xml كسلسلة UTF-8. |
| [getXmlData()](#getXmlData--) | إرجاع أو تعيين بيانات xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | إرجاع أو تعيين بيانات xml. |
| [getItemId()](#getItemId--) | يحدد معرّفًا فريدًا عالميًا (GUID) يميّز جزء XML مخصص واحد داخل مستند Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | يحدد معرّفًا فريدًا عالميًا (GUID) يميّز جزء XML مخصص واحد داخل مستند Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | إرجاع مجموعة مخططات XML المرتبطة بالجزء XML المخصص. |
| [remove()](#remove--) | إزالة الجزء XML المخصص من العرض التقديمي. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

إرجاع أو تعيين بيانات xml كسلسلة UTF-8. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

إرجاع أو تعيين بيانات xml كسلسلة UTF-8. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

إرجاع أو تعيين بيانات xml. قراءة/كتابة byte[].

**القيمة المرجعة:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

إرجاع أو تعيين بيانات xml. قراءة/كتابة byte[].

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

يحدد معرّفًا فريدًا عالميًا (GUID) يميّز جزء XML مخصص واحد داخل مستند Office Open XML. قراءة فقط java.util.UUID.

**القيمة المرجعة:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

يحدد معرّفًا فريدًا عالميًا (GUID) يميّز جزء XML مخصص واحد داخل مستند Office Open XML. قراءة فقط java.util.UUID.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

إرجاع مجموعة مخططات XML المرتبطة بالجزء XML المخصص. قراءة فقط String[].

**القيمة المرجعة:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

إزالة الجزء XML المخصص من العرض التقديمي.