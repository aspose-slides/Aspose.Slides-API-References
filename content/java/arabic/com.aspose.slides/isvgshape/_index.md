---
title: ISvgShape
second_title: Aspose.Slides لـ Java API Reference
description: يمثل الخيارات لشكل SVG.
type: docs
url: /ar/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

يمثل الخيارات لشكل SVG.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | يضبط معالج الحدث للشكل |
| [getId()](#getId--) | يضبط أو يحصل على id للشكل |
| [setId(String value)](#setId-java.lang.String-) | يضبط أو يحصل على id للشكل |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

يضبط معالج الحدث للشكل

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| eventType | int | نوع الحدث. |
| handler | java.lang.String | دالة Javascript لمعالجة الحدث. القيمة Null تُزيل المعالج. |

### getId() {#getId--}
```
public abstract String getId()
```

يضبط أو يحصل على id للشكل

**الإرجاع:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

يضبط أو يحصل على id للشكل

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |