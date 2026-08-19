---
title: ISvgShape
second_title: Aspose.Slides for Java API Reference
description: Represents options for SVG shape.
type: docs
url: /fa/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

نمایانگر گزینه‌های شکل SVG است.
## متدها

| متد | توضیح |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Sets event handler for the shape |
| [getId()](#getId--) | Sets or gets id for the shape |
| [setId(String value)](#setId-java.lang.String-) | Sets or gets id for the shape |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


رویدادگیر برای شکل تنظیم می‌شود

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| eventType | int | نوع رویداد. |
| handler | java.lang.String | تابع Javascript برای پردازش رویداد. مقدار Null هندلر را حذف می‌کند. |

### getId() {#getId--}
```
public abstract String getId()
```


تنظیم یا دریافت شناسه برای شکل

**بازگشت:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


تنظیم یا دریافت شناسه برای شکل

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |