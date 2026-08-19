---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents common slide view properties.
type: docs
url: /fa/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

نمایش کلی ویژگی‌های اسلاید مشترک را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getScale()](#getScale--) | نسبت مقیاس نمایش را بر حسب درصد مشخص می‌کند. |
| [setScale(int value)](#setScale-int-) | نسبت مقیاس نمایش را بر حسب درصد مشخص می‌کند. |
| [getVariableScale()](#getVariableScale--) | مشخص می‌کند که محتوای نما به‌صورت خودکار برای بهترین تناسب با اندازه پنجره فعلی مقیاس‌بندی شود. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | مشخص می‌کند که محتوای نما به‌صورت خودکار برای بهترین تناسب با اندازه پنجره فعلی مقیاس‌بندی شود. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه راهنمای‌های رسم را برمی‌گرداند. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


نسبت مقیاس نمایش را بر حسب درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**باز می‌گردد:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


نسبت مقیاس نمایش را بر حسب درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


مشخص می‌کند که محتوای نما به‌صورت خودکار برای بهترین تناسب با اندازه پنجره فعلی مقیاس‌بندی شود. قابل خواندن/نوشتن boolean.

**باز می‌گردد:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


مشخص می‌کند که محتوای نما به‌صورت خودکار برای بهترین تناسب با اندازه پنجره فعلی مقیاس‌بندی شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


مجموعه راهنمای‌های رسم را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // اضافه کردن راهنمای عمودی جدید به سمت راست مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // اضافه کردن راهنمای افقی جدید به زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)