---
title: Portion
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر بخشی از متن داخل یک پاراگراف متن است.
type: docs
url: /fa/com.aspose.slides/portion/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

نمایانگر بخشی از متن داخل یک بند متن است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Portion()](#Portion--) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |
| [Portion(String str)](#Portion-java.lang.String-) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | یک شیء قالب‌بندی را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی تنظیم‌شده صریحاً برای بخش متن است که هیچ ارث‌بری اعمال نشده است. |
| [getText()](#getText--) | متن ساده یک بخش را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک بخش را دریافت یا تنظیم می‌کند. |
| [getField()](#getField--) | یک فیلد از این بخش را برمی‌گرداند. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | این بخش را به فیلد به‌روز شده به‌صورت خودکار تبدیل می‌کند. |
| [addField(String internalString)](#addField-java.lang.String-) | این بخش را به فیلد به‌روز شده به‌صورت خودکار تبدیل می‌کند. |
| [removeField()](#removeField--) | این بخش فیلد را به بخش ساده تبدیل می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که مرزبندی بخش را دارد دریافت می‌کند. |
| [getCoordinates()](#getCoordinates--) | مختصات آغاز بخش را دریافت می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد متن را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه‌کننده والد متن را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


یک شیء قالب‌بندی را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی تنظیم‌شده صریحاً برای بخش متن است که هیچ ارث‌بری اعمال نشده است. فقط-خواندنی [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

شیء قالب‌بندی تنها شامل پارامترهای قالب‌بندی تعریف‌شده برای بخش فعلی است و داده‌های ارث‌بری اعمال نمی‌شود.

برای دریافت مقادیر موثر شامل مقادیر ارث‌بری، از متد [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) استفاده کنید.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


متن ساده یک بخش را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


متن ساده یک بخش را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


یک فیلد از این بخش را برمی‌گرداند. فقط-خواندنی [IField](../../com.aspose.slides/ifield).

**بازگشت:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


این بخش را به فیلد به‌روز شده به‌صورت خودکار تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


این بخش را به فیلد به‌روز شده به‌صورت خودکار تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| internalString | java.lang.String | نام داخلی FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```


این بخش فیلد را به بخش ساده تبدیل می‌کند.

### getRect() {#getRect--}
```
public final RectF getRect()
```


مختصات مستطیلی که مرزبندی بخش را دارد دریافت می‌کند. این مستطیل شامل تمام خطوط متن در بخش، از جمله خطوط خالی است.

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
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```


مختصات آغاز بخش را دریافت کنید. مختصات X نقطه شروع بخش از کاراکتر اول را شامل جانبی چپ نشان می‌دهد. مختصات Y شامل جانبی بالا است.

**بازگشت:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


اسلاید والد متن را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


ارائه‌کننده والد متن را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject