---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /vi/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính định dạng bullet hiệu quả cho đoạn văn.

--------------------

Giao diện này được sử dụng như một phần của [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về loại bullet của một đoạn văn. |
| [getChar()](#getChar--) | Trả về ký tự bullet của một đoạn văn. |
| [getActualBulletValue()](#getActualBulletValue--) | Trả về giá trị bullet thực tế cho đoạn văn cha. |
| [getFont()](#getFont--) | Trả về phông chữ bullet của một đoạn văn. |
| [getHeight()](#getHeight--) | Trả về chiều cao bullet của một đoạn văn. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Trả về số đầu tiên được sử dụng cho nhóm các bullet có số thứ tự. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Trả về kiểu của bullet có số thứ tự. |
| [isBulletHardColor()](#isBulletHardColor--) | Xác định xem bullet có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [isBulletHardFont()](#isBulletHardFont--) | Xác định xem bullet có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [getPicture()](#getPicture--) | Trả về hình ảnh được sử dụng làm bullet trong đoạn văn. |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng tô đầy bullet của một đoạn văn. |
### getType() {#getType--}
```
public abstract byte getType()
```


Trả về loại bullet của một đoạn văn. Chỉ đọc [BulletType](../../com.aspose.slides/bullettype).

**Trả về:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Trả về ký tự bullet của một đoạn văn. Chỉ đọc char.

**Trả về:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Trả về giá trị bullet thực tế cho đoạn văn cha. Chỉ đọc String.

**Trả về:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Trả về phông chữ bullet của một đoạn văn. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Trả về chiều cao bullet của một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Trả về số đầu tiên được sử dụng cho nhóm các bullet có số thứ tự. Chỉ đọc short.

**Trả về:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Trả về kiểu của bullet có số thứ tự. Chỉ đọc [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Trả về:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Xác định xem bullet có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. Trả về **true** nếu bullet có màu riêng và **false** nếu bullet kế thừa màu từ phần đầu tiên trong đoạn văn. Chỉ đọc boolean.

**Trả về:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Xác định xem bullet có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. Trả về **true** nếu bullet có phông chữ riêng và **true** nếu bullet kế thừa phông chữ từ phần đầu tiên trong đoạn văn. Chỉ đọc boolean.

**Trả về:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Trả về hình ảnh được sử dụng làm bullet trong đoạn văn. Chỉ đọc [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Trả về:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Trả về định dạng tô đầy bullet của một đoạn văn. Chỉ đọc [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Giả sử hình dạng đầu tiên trên slide đầu tiên là AutoShape có một số văn bản...
>      // Xuất thông tin về bullet của các đoạn văn bản
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


**Trả về:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)