---
title: ISvgShape
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل خيارات لشكل SVG.
type: docs
url: /ar/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

يمثل خيارات لشكل SVG.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | يضبط معالج الحدث للشكل |
| [getId()](#getId--) | يضبط أو يحصل على المعرف للشكل |
| [setId(String value)](#setId-java.lang.String-) | يضبط أو يحصل على المعرف للشكل |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


يضبط معالج الحدث للشكل

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| eventType | int | نوع الحدث. |
| handler | java.lang.String | وظيفة جافاسكريبت لمعالجة الحدث. القيمة null تُزيل المعالج. |

### getId() {#getId--}
```
public abstract String getId()
```


يضبط أو يحصل على المعرف للشكل

**القيمة المرتجعة:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


يضبط أو يحصل على المعرف للشكل

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |