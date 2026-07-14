---
title: HtmlExternalResolver
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: كائن رد النداء المستخدم بواسطة روتين استيراد HTML للحصول على الكائنات المشار إليها مثل الصور.
type: docs
url: /ar/com.aspose.slides/htmlexternalresolver/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

كائن رد نداء يُستخدم بواسطة روتين استيراد HTML للحصول على الكائنات المشار إليها مثل الصور.

--------------------

استخدام هذا المحلّل قد يُنشئ ثغرة عندما يُقدِّم العميل ملف HTML يجعل برنامج الخادم يحصل على ملف محلي أو عبر الشبكة. استخدمه بحذر. يُنصح بعدم تحديد HtmlExternalResolver على الإطلاق (سيتم قراءة الكائنات المدمجة فقط) أو إنشاء فئة فرعية تتحقق مما إذا كان uri المحدد صالحًا.
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | يحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | يربط URI بكائن يحتوي على المورد الفعلي. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


يحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | java.lang.String | URI الأساسي للكائنات المرتبطة |
| relativeUri | java.lang.String | URI النسبي إلى الكائن المرتبط. |

**القيمة المرجعة:**
java.lang.String - URI مطلق أو null إذا تعذّر حل الـ URI النسبي.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


يُربط URI بكائن يحتوي على المورد الفعلي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق إلى الكائن. |

**القيمة المرجعة:**
java.io.InputStream - كائن InputStream أو null إذا تعذّر بث المورد.