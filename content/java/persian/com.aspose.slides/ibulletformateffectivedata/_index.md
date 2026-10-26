---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی گلوله (bullet) پاراگراف مؤثر است.
type: docs
url: /fa/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی گلوله پاراگراف مؤثر است.

--------------------

این رابط به عنوان بخشی از [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | نوع گلوله یک پاراگراف را برمی‌گرداند. |
| [getChar()](#getChar--) | کاراکتر گلوله یک پاراگراف را برمی‌گرداند. |
| [getActualBulletValue()](#getActualBulletValue--) | مقدار واقعی گلوله برای پاراگراف والد را برمی‌گرداند. |
| [getFont()](#getFont--) | فونت گلوله یک پاراگراف را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع گلوله یک پاراگراف را برمی‌گرداند. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | اولین عددی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را برمی‌گرداند. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | سبک گلوله شماره‌دار را برمی‌گرداند. |
| [isBulletHardColor()](#isBulletHardColor--) | تشخیص می‌دهد که آیا گلوله رنگ اختصاصی دارد یا از اولین بخش پاراگراف به ارث می‌برد. |
| [isBulletHardFont()](#isBulletHardFont--) | تشخیص می‌دهد که آیا گلوله فونت اختصاصی دارد یا از اولین بخش پاراگراف به ارث می‌برد. |
| [getPicture()](#getPicture--) | تصویر استفاده‌شده به‌عنوان گلوله در پاراگراف را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | قالب پر شدن گلوله یک پاراگراف را برمی‌گرداند. |
### getType() {#getType--}
```
public abstract byte getType()
```


نوع گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [BulletType](../../com.aspose.slides/bullettype).

**برمی‌گرداند:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


کاراکتر گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی char.

**برمی‌گرداند:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


مقدار واقعی گلوله برای پاراگراف والد را برمی‌گرداند. فقط خواندنی String.

**برمی‌گرداند:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


فونت گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**برمی‌گرداند:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


ارتفاع گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**برمی‌گرداند:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


اولین عددی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را برمی‌گرداند. فقط خواندنی short.

**برمی‌گرداند:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


سبک گلوله شماره‌دار را برمی‌گرداند. فقط خواندنی [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**برمی‌گرداند:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


تشخیص می‌دهد که آیا گلوله رنگ اختصاصی دارد یا از اولین بخش پاراگراف به ارث می‌برد. **true** برمی‌گرداند اگر گلوله رنگ اختصاصی داشته باشد و **false** اگر رنگ را از اولین بخش پاراگراف به ارث ببرد. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


تشخیص می‌دهد که آیا گلوله فونت اختصاصی دارد یا از اولین بخش پاراگراف به ارث می‌برد. **true** برمی‌گرداند اگر گلوله فونت اختصاصی داشته باشد و **true** اگر فونت را از اولین بخش پاراگراف به ارث ببرد. فقط خواندنی boolean.

**برمی‌گرداند:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


تصویر استفاده‌شده به‌عنوان گلوله در پاراگراف را برمی‌گرداند. فقط خواندنی [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**برمی‌گرداند:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


قالب پر شدن گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // فرض کنید اولین شکل در اولین اسلاید یک AutoShape با متنی است...
>      // اطلاعات مربوط به گلوله‌های پاراگراف‌های متنی را خروجی دهید
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


**برمی‌گرداند:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)