---
title: IExternalResourceResolver
second_title: Aspose.Slides للـ Java مرجع API
description: واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.
type: docs
url: /ar/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.
## الطرق

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | يُحَل الـ URI المطلق من الـ base URI والـ relative URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | يربط URI بكائن يحتوي على المورد الفعلي. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

يُحَل الـ URI المطلق من الـ base URI والـ relative URI.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | الـ base URI للكائنات المرتبطة |
| relativeUri | java.lang.String | الـ relative URI للكائن المرتبط. |

**القيمة المرجعة:**
java.lang.String - URI مطلق أو null إذا تعذر حل الـ relative URI.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

يربط URI بكائن يحتوي على المورد الفعلي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | الـ absolute URI إلى الكائن. |

**القيمة المرجعة:**
java.io.InputStream - كائن InputStream أو null إذا تعذر بث المورد.