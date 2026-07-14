---
title: IPortion
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک بخش از متن داخل یک پاراگراف متن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iportion/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

یک بخش از متن داخل پاراگراف متن را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | یک شی فرمت‌بندی را برمی‌گرداند که شامل ویژگی‌های صریحاً تنظیم‌شدهٔ بخش متن است بدون اعمال وراثت. |
| [getText()](#getText--) | متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. |
| [getField()](#getField--) | یک فیلد از این بخش را برمی‌گرداند. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | این بخش را به فیلد به‌روز‌شده خودکار تبدیل می‌کند. |
| [addField(String internalString)](#addField-java.lang.String-) | این بخش را به فیلد به‌روز‌شده خودکار تبدیل می‌کند. |
| [removeField()](#removeField--) | این بخش فیلد را به بخش ساده تبدیل می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که بخش را محدود می‌کند دریافت می‌کند. |
| [getCoordinates()](#getCoordinates--) | مختصات شروع بخش را دریافت می‌کند. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

یک شی فرمت‌بندی را برمی‌گرداند که شامل ویژگی‌های صریحاً تنظیم‌شدهٔ بخش متن است بدون اعمال وراثت. فقط-خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

شی فرمت‌بندی فقط شامل پارامترهای فرمت‌بندی تعریف‌شده برای بخش جاری است و داده‌های وارثت‌شده اعمال نمی‌شوند.

برای دریافت مقادیر موثر شامل مقادیر وارثت‌شده، از متد [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید.

**بازگشت:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**بازگشت:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

یک فیلد از این بخش را برمی‌گرداند. فقط-خواندنی [IField](../../com.aspose.slides/ifield).

**بازگشت:**  
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

این بخش را به فیلد به‌روز‌شده خودکار تبدیل می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | نوع فیلد [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

این بخش را به فیلد به‌روز‌شده خودکار تبدیل می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| internalString | java.lang.String | نام داخلی FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

این بخش فیلد را به بخش ساده تبدیل می‌کند.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

مختصات مستطیلی که بخش را محدود می‌کند دریافت می‌کند. این مستطیل شامل تمام خطوط متن در بخش، حتی خطوط خالی است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
android.graphics.RectF - مستطیلی که بخش را محدود می‌کند android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

مختصات شروع بخش را دریافت می‌کند. مختصات X نقطه نشان‌دهندهٔ شروع بخش از اولین کاراکتر به‌همراه فاصلهٔ سمت چپ است. مختصات Y شامل فاصلهٔ سمت بالا می‌باشد.

**بازگشت:**  
android.graphics.PointF - مختصات شروع بخش android.graphics.PointF