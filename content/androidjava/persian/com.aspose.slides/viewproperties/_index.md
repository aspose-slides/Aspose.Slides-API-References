---
title: ViewProperties
second_title: Aspose.Slides برای Android – مرجع API جاوا
description: ویژگی‌های نمای کلی ارائه.
type: docs
url: /fa/com.aspose.slides/viewproperties/
---
**وارثی:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

ویژگی‌های نمای کلی ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getLastView()](#getLastView--) | حالت نمایشی را که هنگام ذخیره‌سازی آخرین سند ارائه استفاده شده بود، مشخص می‌کند. |
| [setLastView(int value)](#setLastView-int-) | حالت نمایشی را که هنگام ذخیره‌سازی آخرین سند ارائه استفاده شده بود، مشخص می‌کند. |
| [getShowComments()](#getShowComments--) | مشخص می‌کند آیا نظرات اسلاید باید نمایش داده شوند یا خیر. |
| [setShowComments(byte value)](#setShowComments-byte-) | مشخص می‌کند آیا نظرات اسلاید باید نمایش داده شوند یا خیر. |
| [getNormalViewProperties()](#getNormalViewProperties--) | ویژگی‌های نمای عادی را نشان می‌دهد. |
| [getSlideViewProperties()](#getSlideViewProperties--) | ویژگی‌های عمومی نمای مرتبط با حالت نمای اسلاید را مشخص می‌کند. |
| [getNotesViewProperties()](#getNotesViewProperties--) | ویژگی‌های عمومی نمای مرتبط با حالت نمای یادداشت‌ها را مشخص می‌کند. |
| [getGridSpacing()](#getGridSpacing--) | فاصله شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | فاصله شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

حالت نمایشی را که هنگام ذخیره‌سازی آخرین سند ارائه استفاده شده بود، مشخص می‌کند. خواندنی/نوشتنی [ViewType](../../com.aspose.slides/viewtype).

**بازگشت:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

حالت نمایشی را که هنگام ذخیره‌سازی آخرین سند ارائه استفاده شده بود، مشخص می‌کند. خواندنی/نوشتنی [ViewType](../../com.aspose.slides/viewtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

مشخص می‌کند آیا نظرات اسلاید باید نمایش داده شوند یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

مشخص می‌کند آیا نظرات اسلاید باید نمایش داده شوند یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

ویژگی‌های نمای عادی را نشان می‌دهد. نمای عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا جانبی و یک ناحیه محتوا پایین. فقط‌خواندنی [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**بازگشت:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

ویژگی‌های عمومی نمای مرتبط با حالت نمای اسلاید را مشخص می‌کند. فقط‌خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

ویژگی‌های عمومی نمای مرتبط با حالت نمای یادداشت‌ها را مشخص می‌کند. فقط‌خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

فاصله شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> کد نمونه زیر نشان می‌دهد چگونه فاصله شبکه را در یک ارائه PowerPoint تغییر دهیم.
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

مقدار فاصله شبکه باید یک عدد مثبت باشد. بازه مقدار معمول از ۱ میلی‌متر (۲.۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**بازگشت:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

فاصله شبکه را که باید برای شبکه زیرین سند ارائه استفاده شود، بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------

> ```
> کد نمونه زیر نشان می‌دهد چگونه فاصله شبکه را در یک ارائه PowerPoint تغییر دهیم.
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

مقدار فاصله شبکه باید یک عدد مثبت باشد. بازه مقدار معمول از ۱ میلی‌متر (۲.۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject