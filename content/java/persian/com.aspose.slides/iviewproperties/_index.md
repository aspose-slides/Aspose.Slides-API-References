---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /fa/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

ویژگی‌های نمای کلی ارائه.

## متدها

| متد | توضیح |
| --- | --- |
| [getLastView()](#getLastView--) | حالت نمایشی را مشخص می‌کند که هنگام آخرین ذخیره‌سازی سند ارائه مورد استفاده قرار گرفته بود. |
| [setLastView(int value)](#setLastView-int-) | حالت نمایشی را مشخص می‌کند که هنگام آخرین ذخیره‌سازی سند ارائه مورد استفاده قرار گرفته بود. |
| [getShowComments()](#getShowComments--) | تعیین می‌کند که نظرات اسلاید باید نمایش داده شوند یا خیر. |
| [setShowComments(byte value)](#setShowComments-byte-) | تعیین می‌کند که نظرات اسلاید باید نمایش داده شوند یا خیر. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ویژگی‌های نمای مشترکی را که با حالت نمای اسلاید مرتبط هستند، مشخص می‌کند. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ویژگی‌های نمای مشترکی را که با حالت نمای یادداشت‌ها مرتبط هستند، مشخص می‌کند. |
| [getNormalViewProperties()](#getNormalViewProperties--) | ویژگی‌های نمای عادی را نمایان می‌سازد. |
| [getGridSpacing()](#getGridSpacing--) | فاصله‌بندی شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، به پوینت برمی‌گرداند یا تنظیم می‌کند. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | فاصله‌بندی شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، به پوینت برمی‌گرداند یا تنظیم می‌کند. |

### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

حالت نمایشی را مشخص می‌کند که هنگام آخرین ذخیره‌سازی سند ارائه مورد استفاده قرار گرفته بود. خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**بازگشت:**
int

### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

حالت نمایشی را مشخص می‌کند که هنگام آخرین ذخیره‌سازی سند ارائه مورد استفاده قرار گرفته بود. خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

تعیین می‌کند که نظرات اسلاید باید نمایش داده شوند یا خیر. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

تعیین می‌کند که نظرات اسلاید باید نمایش داده شوند یا خیر. خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

ویژگی‌های نمای مشترکی را که با حالت نمای اسلاید مرتبط هستند، مشخص می‌کند. فقط-خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

ویژگی‌های نمای مشترکی را که با حالت نمای یادداشت‌ها مرتبط هستند، مشخص می‌کند. فقط-خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

ویژگی‌های نمای عادی را نمایان می‌سازد. نمای عادی شامل سه ناحیه محتوایی است: خود اسلاید، یک ناحیه محتوای جانبی، و یک ناحیه محتوای پایین. فقط-خواندنی [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**بازگشت:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

فاصله‌بندی شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، به پوینت برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

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

مقدار فاصله‌بندی شبکه باید عددی مثبت باشد. بازهٔ مقدار معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ پوینت) تا ۲ اینچ (۱۴۴ پوینت) است.

**بازگشت:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

فاصله‌بندی شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، به پوینت برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

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

مقدار فاصله‌بندی شبکه باید عددی مثبت باشد. بازهٔ مقدار معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ پوینت) تا ۲ اینچ (۱۴۴ پوینت) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |