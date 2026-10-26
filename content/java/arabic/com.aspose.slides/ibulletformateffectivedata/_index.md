---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides لـ Java مرجع API
description: كائن غير قابل للتعديل يحتوي على خصائص تنسيق نقاط الفقرة الفعّالة.
type: docs
url: /ar/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

كائن غير قابل للتعديل يحتوي على خصائص تنسيق نقاط الفقرة الفعّالة.

--------------------

هذه الواجهة تُستخدم كجزء من [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يعيد نوع الرصاصة للفقرة. |
| [getChar()](#getChar--) | يعيد حرف الرصاصة للفقرة. |
| [getActualBulletValue()](#getActualBulletValue--) | يعيد القيمة الفعلية للرصاصة للفقرة الأصلية. |
| [getFont()](#getFont--) | يعيد خط الرصاصة للفقرة. |
| [getHeight()](#getHeight--) | يعيد ارتفاع الرصاصة للفقرة. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | يعيد الرقم الأول الذي يُستخدم لمجموعة من الرصاصات المرقمة. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | يعيد نمط الرصاصة المرقمة. |
| [isBulletHardColor()](#isBulletHardColor--) | يحدد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. |
| [isBulletHardFont()](#isBulletHardFont--) | يحدد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. |
| [getPicture()](#getPicture--) | يعيد الصورة المستخدمة كرصاصة في الفقرة. |
| [getFillFormat()](#getFillFormat--) | يعيد تنسيق تعبئة الرصاصة للفقرة. |
### getType() {#getType--}
```
public abstract byte getType()
```

يعيد نوع الرصاصة للفقرة. للقراءة فقط [BulletType](../../com.aspose.slides/bullettype).

**الإرجاع:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

يعيد حرف الرصاصة للفقرة. للقراءة فقط char.

**الإرجاع:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

يعيد القيمة الفعلية للرصاصة للفقرة الأصلية. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

يعيد خط الرصاصة للفقرة. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

يعيد ارتفاع الرصاصة للفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

يعيد الرقم الأول الذي يُستخدم لمجموعة من الرصاصات المرقمة. للقراءة فقط short.

**الإرجاع:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

يعيد نمط الرصاصة المرقمة. للقراءة فقط [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**الإرجاع:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

يحدد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. تُعيد **true** إذا كان للرصاصة لون خاص و **false** إذا كانت الرصاصة ترث اللون من الجزء الأول في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

يحدد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. تُعيد **true** إذا كان للرصاصة خط خاص و **true** إذا كانت الرصاصة ترث الخط من الجزء الأول في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

يعيد الصورة المستخدمة كرصاصة في الفقرة. للقراءة فقط [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**الإرجاع:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

يعيد تنسيق تعبئة الرصاصة للفقرة. للقراءة فقط [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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