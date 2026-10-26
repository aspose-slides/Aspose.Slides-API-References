---
title: ViewProperties
second_title: مرجع API Aspose.Slides for Java
description: ویژگی‌های نمای کلی ارائه.
type: docs
url: /fa/com.aspose.slides/viewproperties/
---
**ارث‌بری:**  
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject  
```
public class ViewProperties implements IViewProperties, IDOMObject
```

ویژگی‌های نمای کلی ارائه.

## متدها

| متد | توضیح |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getGridSpacing()](#getGridSpacing--) | مقدار یا تنظیم فاصلهٔ شبکه‌ای که برای شبکهٔ زیر سند ارائه استفاده می‌شود، به نقطه. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | مقدار یا تنظیم فاصلهٔ شبکه‌ای که برای شبکهٔ زیر سند ارائه استفاده می‌شود، به نقطه. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

حالت نمایی که هنگام آخرین ذخیره‌سازی سند ارائه استفاده شده بود را مشخص می‌کند. قابل خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**بازگشت:**  
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

حالت نمایی که هنگام آخرین ذخیره‌سازی سند ارائه استفاده شده بود را مشخص می‌کند. قابل خواندن/نوشتن [ViewType](../../com.aspose.slides/viewtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

مشخص می‌کند که آیا نظرات اسلاید باید نشان داده شوند یا خیر. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**  
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

مشخص می‌کند که آیا نظرات اسلاید باید نشان داده شوند یا خیر. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

نمای عادی را توصیف می‌کند. نمای عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا کناری و یک ناحیه محتوا پایینی. فقط-خواندنی [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**بازگشت:**  
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

مشخصات مشترک نمایی که با حالت نمایش اسلاید مرتبط است را ارائه می‌دهد. فقط-خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

مشخصات مشترک نمایی که با حالت نمایش یادداشت‌ها مرتبط است را ارائه می‌دهد. فقط-خواندنی [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**بازگشت:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

مقدار یا تنظیم فاصلهٔ شبکه‌ای که برای شبکهٔ زیر سند ارائه استفاده می‌شود، به نقطه. قابل خواندن/نوشتن float.

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

مقدار فاصلهٔ شبکه باید عددی مثبت باشد. بازهٔ معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**بازگشت:**  
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

مقدار یا تنظیم فاصلهٔ شبکه‌ای که برای شبکهٔ زیر سند ارائه استفاده می‌شود، به نقطه. قابل خواندن/نوشتن float.

--------------------

> ```
> کد نمونهٔ زیر نشان می‌دهد چگونه فاصلهٔ شبکه را در یک ارائهٔ PowerPoint تغییر دهیم.
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

مقدار فاصلهٔ شبکه باید عددی مثبت باشد. بازهٔ معمولی از ۱ میلی‌متر (۲٫۸۳۴۹۶۰۷ نقطه) تا ۲ اینچ (۱۴۴ نقطه) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject