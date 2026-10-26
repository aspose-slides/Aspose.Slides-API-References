---
title: IPortion
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر بخشی از متن داخل یک پاراگراف متنی است.
type: docs
url: /fa/com.aspose.slides/iportion/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

نمایانگر بخشی از متن داخل یک پاراگراف متنی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | یک شیء قالب‌بندی را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی به‌ طور صریح تنظیم شدهٔ بخش متن است و هیچ وراثتی اعمال نمی‌شود. |
| [getText()](#getText--) | متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. |
| [getField()](#getField--) | یک فیلد از این بخش را برمی‌گرداند. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | این بخش را به فیلدی که به‌ طور خودکار به‌روز می‌شود تبدیل می‌کند. |
| [addField(String internalString)](#addField-java.lang.String-) | این بخش را به فیلدی که به‌ طور خودکار به‌روز می‌شود تبدیل می‌کند. |
| [removeField()](#removeField--) | این بخش فیلد را به بخش ساده تبدیل می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که بخش را محاط می‌کند دریافت می‌کند. |
| [getCoordinates()](#getCoordinates--) | مختصات آغاز بخش را دریافت می‌کند. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


یک شیء قالب‌بندی را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی به‌ طور صریح تنظیم شدهٔ بخش متن است و هیچ وراثتی اعمال نمی‌شود. فقط خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

شیء قالب‌بندی شامل پارامترهای قالب‌بندی تعریف‌شده برای بخش فعلی است؛ داده‌های ارث‌برده اعمال نمی‌شوند.

برای دریافت مقادیر مؤثر شامل مقادیر ارث‌برده، از روش [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن String.

مقدار: متن.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


متن سادهٔ یک بخش را دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```


یک فیلد از این بخش را برمی‌گرداند. فقط خواندنی [IField](../../com.aspose.slides/ifield).

**بازگشت:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


این بخش را به فیلدی که به‌ طور خودکار به‌روز می‌شود تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | نوع فیلد [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


این بخش را به فیلدی که به‌ طور خودکار به‌روز می‌شود تبدیل می‌کند.

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
public abstract Rectangle2D.Float getRect()
```


مختصات مستطیلی که بخش را محاط می‌کند دریافت می‌کند. مستطیل شامل تمام خطوط متن در بخش است، حتی خطوط خالی.

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
java.awt.geom.Rectangle2D.Float - مستطیلی که بخش را محاط می‌کند java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


مختصات آغاز بخش را دریافت می‌کند. مختصات X نقطه نمایانگر آغاز بخش از اولین کاراکتر شامل بردار سمت چپ است. مختصات Y شامل بردار سمت بالایی است.

**بازگشت:**
java.awt.geom.Point2D.Float - مختصات آغاز بخش java.awt.geom.Point2D.Float