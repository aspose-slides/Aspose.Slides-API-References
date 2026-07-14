---
title: TextStyle
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบสไตล์ข้อความ.
type: docs
url: /th/com.aspose.slides/textstyle/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบสไตล์ข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | หากระดับสไตล์มีอยู่จะคืนค่าระดับนั้น มิฉะนั้นจะคืนค่า null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | คุณสมบัติย่อหน้าเริ่มต้น. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลโดยคำนึงถึงการสืบทอด. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


หากระดับสไตล์มีอยู่จะคืนค่าระดับนั้น มิฉะนั้นจะคืนค่า null.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของระดับ ต้องอยู่ในช่วง 0..8. |

**คืนค่า:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - การจัดรูปแบบของระดับ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


คุณสมบัติย่อหน้าเริ่มต้น. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**คืนค่า:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลโดยคำนึงถึงการสืบทอด.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - เป็น [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).