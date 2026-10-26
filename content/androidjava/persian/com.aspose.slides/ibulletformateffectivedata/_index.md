---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /fa/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های فرمت‌بندی گلوله مؤثر پاراگراف است.

--------------------

این رابط به عنوان بخشی از [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) استفاده می‌شود.
## متدها

| Method | Description |
| --- | --- |
| [getType()](#getType--) | نوع گلوله یک پاراگراف را برمی‌گرداند. |
| [getChar()](#getChar--) | کاراکتر گلوله یک پاراگراف را برمی‌گرداند. |
| [getActualBulletValue()](#getActualBulletValue--) | مقدار واقعی گلوله برای پاراگراف والد را برمی‌گرداند. |
| [getFont()](#getFont--) | قلم گلوله یک پاراگراف را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع گلوله یک پاراگراف را برمی‌گرداند. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | اولین عددی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را برمی‌گرداند. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | سبک یک گلوله شماره‌دار را برمی‌گرداند. |
| [isBulletHardColor()](#isBulletHardColor--) | تعیین می‌کند که آیا گلوله رنگ اختصاصی دارد یا از اولین بخش پاراگراف ارث‌برسد. |
| [isBulletHardFont()](#isBulletHardFont--) | تعیین می‌کند که آیا گلوله قلم اختصاصی دارد یا از اولین بخش پاراگراف ارث‌برسد. |
| [getPicture()](#getPicture--) | تصویر استفاده‌شده به عنوان گلوله در پاراگراف را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | فرمت پر کردن گلوله یک پاراگراف را برمی‌گرداند. |
### getType() {#getType--}
```
public abstract byte getType()
```


نوع گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [BulletType](../../com.aspose.slides/bullettype).

**باز می‌گردد:**  
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


کاراکتر گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی char.

**باز می‌گردد:**  
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


مقدار واقعی گلوله برای پاراگراف والد را برمی‌گرداند. فقط خواندنی String.

**باز می‌گردد:**  
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


قلم گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [IFontData](../../com.aspose.slides/ifontdata).

**باز می‌گردد:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


ارتفاع گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی float.

**باز می‌گردد:**  
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


اولین عددی که برای گروهی از گلوله‌های شماره‌دار استفاده می‌شود را برمی‌گرداند. فقط خواندنی short.

**باز می‌گردد:**  
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


سبک یک گلوله شماره‌دار را برمی‌گرداند. فقط خواندنی [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**باز می‌گردد:**  
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


تعیین می‌کند که آیا گلوله رنگ اختصاصی دارد یا از اولین بخش پاراگراف ارث‌بربگیرد. اگر گلوله رنگ اختصاصی داشته باشد **true** و اگر رنگ را از اولین بخش پاراگراف ارث‌بگیرد **false** برمی‌گرداند. فقط خواندنی boolean.

**باز می‌گردد:**  
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


تعیین می‌کند که آیا گلوله قلم اختصاصی دارد یا از اولین بخش پاراگراف ارث‌بربگیرد. اگر گلوله قلم اختصاصی داشته باشد **true** و اگر قلم را از اولین بخش پاراگراف ارث‌بگیرد **true** برمی‌گرداند. فقط خواندنی boolean.

**باز می‌گردد:**  
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


تصویری که به عنوان گلوله در پاراگراف استفاده می‌شود را برمی‌گرداند. فقط خواندنی [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**باز می‌گردد:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


فرمت پر کردن گلوله یک پاراگراف را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // فرض کنید اولین شکل در اولین اسلاید یک AutoShape با متنی است...
>      // اطلاعات مربوط به گلوله‌های پاراگراف‌های متن را نمایش دهید
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


**باز می‌گردد:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)