---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents common slide view properties.
type: docs
url: /fa/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

نمایش ویژگی‌های مشترک اسلاید را نشان می‌دهد.
## Methods

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | نسبت مقیاس نمایشی را به درصد مشخص می‌کند. |
| [setScale(int value)](#setScale-int-) | نسبت مقیاس نمایشی را به درصد مشخص می‌کند. |
| [getVariableScale()](#getVariableScale--) | مشخص می‌کند که محتوای نما به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ فعلی مقیاس بندی شود. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | مشخص می‌کند که محتوای نما به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ فعلی مقیاس بندی شود. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعهٔ خطوط راهنما را برمی‌گرداند. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


نسبت مقیاس نمایشی را به درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**Returns:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


نسبت مقیاس نمایشی را به درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


مشخص می‌کند که محتوای نما به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ فعلی مقیاس بندی شود. قابل خواندن/نوشتن boolean.

**Returns:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


مشخص می‌کند که محتوای نما به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ فعلی مقیاس بندی شود. قابل خواندن/نوشتن boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


مجموعهٔ خطوط راهنما را برمی‌گرداند. فقط‌خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // اضافه کردن راهنمای کششی جدید عمودی به سمت راست مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // اضافه کردن راهنمای کششی جدید افقی زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)