---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: خصوصیات نمایش سراسری ارائه.
type: docs
url: /fa/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

خصوصیات نمایش سراسری ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getLastView()](#getLastView--) | حالت نمایشی که در زمان آخرین ذخیره‌سازی سند ارائه استفاده شده را مشخص می‌کند. |
| [setLastView(int value)](#setLastView-int-) | حالت نمایشی که در زمان آخرین ذخیره‌سازی سند ارائه استفاده شده را مشخص می‌کند. |
| [getShowComments()](#getShowComments--) | مشخص می‌کند که آیا نظرات اسلاید نمایش داده شوند یا نه. |
| [setShowComments(byte value)](#setShowComments-byte-) | مشخص می‌کند که آیا نظرات اسلاید نمایش داده شوند یا نه. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ویژگی‌های نمایش عمومی مرتبط با حالت نمای اسلاید را مشخص می‌کند. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ویژگی‌های نمایش عمومی مرتبط با حالت نمای یادداشت‌ها را مشخص می‌کند. |
| [getNormalViewProperties()](#getNormalViewProperties--) | نمایش عادی را نشان می‌دهد. |
| [getGridSpacing()](#getGridSpacing--) | فاصله‌بندی شبکه‌ای که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه، را برمی‌گرداند یا تنظیم می‌کند. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | فاصله‌بندی شبکه‌ای که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه، را برمی‌گرداند یا تنظیم می‌کند. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

حالت نمایشی که در زمان آخرین ذخیره‌سازی سند ارائه استفاده شده را مشخص می‌کند. قابل خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**بازگشت:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

حالت نمایشی که در زمان آخرین ذخیره‌سازی سند ارائه استفاده شده را مشخص می‌کند. قابل خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

مشخص می‌کند که آیا نظرات اسلاید نمایش داده شوند یا نه. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

مشخص می‌کند که آیا نظرات اسلاید نمایش داده شوند یا نه. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

ویژگی‌های نمایش عمومی مرتبط با حالت نمای اسلاید را مشخص می‌کند. فقط خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ویژگی‌های نمایش عمومی مرتبط با حالت نمای یادداشت‌ها را مشخص می‌کند. فقط خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

نمایش عادی را نشان می‌دهد. نمایش عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا جانبی، و یک ناحیه محتوا در پایین. فقط خواندنی [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**بازگشت:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

فاصله‌بندی شبکه‌ای که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه، را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مقدار فاصله‌بندی شبکه باید عددی مثبت باشد. دامنه مقدار معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**بازگشت:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

فاصله‌بندی شبکه‌ای که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه، را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مقدار فاصله‌بندی شبکه باید عددی مثبت باشد. دامنه مقدار معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |