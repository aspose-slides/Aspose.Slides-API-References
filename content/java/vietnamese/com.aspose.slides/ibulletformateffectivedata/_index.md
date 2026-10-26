---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Đối tượng bất biến chứa các thuộc tính định dạng dấu đầu dòng đoạn văn hiệu lực.
type: docs
url: /vi/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính định dạng dấu đầu dòng đoạn văn hiệu lực.

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về loại dấu đầu dòng của một đoạn văn. |
| [getChar()](#getChar--) | Trả về ký tự dấu đầu dòng của một đoạn văn. |
| [getActualBulletValue()](#getActualBulletValue--) | Trả về giá trị dấu đầu dòng thực tế cho đoạn văn cha. |
| [getFont()](#getFont--) | Trả về phông chữ dấu đầu dòng của một đoạn văn. |
| [getHeight()](#getHeight--) | Trả về chiều cao dấu đầu dòng của một đoạn văn. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Trả về số đầu tiên được sử dụng cho nhóm các dấu đầu dòng được đánh số. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Trả về kiểu của dấu đầu dòng được đánh số. |
| [isBulletHardColor()](#isBulletHardColor--) | Xác định liệu dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [isBulletHardFont()](#isBulletHardFont--) | Xác định liệu dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [getPicture()](#getPicture--) | Trả về hình ảnh được sử dụng làm dấu đầu dòng trong đoạn văn. |
| [getFillFormat()](#getFillFormat--) | Trả về định dạng tô đầy dấu đầu dòng của một đoạn văn. |
### getType() {#getType--}
```
public abstract byte getType()
```


Trả về loại dấu đầu dòng của một đoạn văn. Chỉ đọc [BulletType](../../com.aspose.slides/bullettype).

**Returns:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Trả về ký tự dấu đầu dòng của một đoạn văn. Chỉ đọc char.

**Returns:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Trả về giá trị dấu đầu dòng thực tế cho đoạn văn cha. Chỉ đọc String.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Trả về phông chữ dấu đầu dòng của một đoạn văn. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Trả về chiều cao dấu đầu dòng của một đoạn văn. Chỉ đọc float.

**Returns:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Trả về số đầu tiên được sử dụng cho nhóm các dấu đầu dòng được đánh số. Chỉ đọc short.

**Returns:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Trả về kiểu của dấu đầu dòng được đánh số. Chỉ đọc [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returns:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Xác định liệu dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. Trả về **true** nếu dấu đầu dòng có màu riêng và **false** nếu dấu đầu dòng kế thừa màu từ phần đầu tiên trong đoạn văn. Chỉ đọc boolean.

**Returns:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Xác định liệu dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. Trả về **true** nếu dấu đầu dòng có phông chữ riêng và **true** nếu dấu đầu dòng kế thừa phông chữ từ phần đầu tiên trong đoạn văn. Chỉ đọc boolean.

**Returns:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Trả về hình ảnh được sử dụng làm dấu đầu dòng trong đoạn văn. Chỉ đọc [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Trả về định dạng tô đầy dấu đầu dòng của một đoạn văn. Chỉ đọc [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)