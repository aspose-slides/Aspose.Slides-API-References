---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق تعداد الفقرات الفعّالة.
type: docs
url: /ar/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق تعداد الفقرات الفعّالة.

--------------------

يُستخدم هذا الواجهة كجزء من [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع نوع تعداد الفقرة. |
| [getChar()](#getChar--) | إرجاع حرف تعداد الفقرة. |
| [getActualBulletValue()](#getActualBulletValue--) | إرجاع القيمة الفعلية للتعداد للفقرة الأصلية. |
| [getFont()](#getFont--) | إرجاع خط تعداد الفقرة. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع تعداد الفقرة. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | إرجاع الرقم الأول المستخدم لمجموعة تعداد رقمي. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | إرجاع نمط تعداد رقمي. |
| [isBulletHardColor()](#isBulletHardColor--) | تحديد ما إذا كان للرقم لون خاص أو يرثه من الجزء الأول في الفقرة. |
| [isBulletHardFont()](#isBulletHardFont--) | تحديد ما إذا كان للرقم خط خاص أو يرثه من الجزء الأول في الفقرة. |
| [getPicture()](#getPicture--) | إرجاع الصورة المستخدمة كعدد في الفقرة. |
| [getFillFormat()](#getFillFormat--) | إرجاع تنسيق تعبئة تعداد الفقرة. |
### getType() {#getType--}
```
public abstract byte getType()
```


إرجاع نوع تعداد الفقرة. للقراءة فقط [BulletType](../../com.aspose.slides/bullettype).

**الإرجاع:**  
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


إرجاع حرف تعداد الفقرة. للقراءة فقط char.

**الإرجاع:**  
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


إرجاع القيمة الفعلية للتعداد للفقرة الأصلية. للقراءة فقط String.

**الإرجاع:**  
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


إرجاع خط تعداد الفقرة. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


إرجاع ارتفاع تعداد الفقرة. للقراءة فقط float.

**الإرجاع:**  
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


إرجاع الرقم الأول المستخدم لمجموعة تعداد رقمي. للقراءة فقط short.

**الإرجاع:**  
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


إرجاع نمط تعداد رقمي. للقراءة فقط [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**الإرجاع:**  
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


تحديد ما إذا كان للعدد لون خاص أو يرثه من الجزء الأول في الفقرة. إرجاع **true** إذا كان للعدد لون خاص و**false** إذا كان يرث اللون من الجزء الأول في الفقرة. للقراءة فقط boolean.

**الإرجاع:**  
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


تحديد ما إذا كان للعدد خط خاص أو يرثه من الجزء الأول في الفقرة. إرجاع **true** إذا كان للعدد خط خاص و**true** إذا كان يرث الخط من الجزء الأول في الفقرة. للقراءة فقط boolean.

**الإرجاع:**  
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


إرجاع الصورة المستخدمة كعدد في الفقرة. للقراءة فقط [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**الإرجاع:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


إرجاع تنسيق تعبئة تعداد الفقرة. للقراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assume that the first shape on the first slide is AutoShape with some text...
>      // Output information about text paragraphs' bullets
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)