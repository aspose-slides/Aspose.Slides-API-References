---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /th/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

อ็อบเจ็กต์ไม่เปลี่ยนแปลงที่บรรจุคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้าที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | คืนค่าประเภทหัวข้อของย่อหน้า |
| [getChar()](#getChar--) | คืนค่าตัวอักษรหัวข้อของย่อหน้า |
| [getActualBulletValue()](#getActualBulletValue--) | คืนค่าค่าหัวข้อที่แท้จริงสำหรับย่อหน้าพาเรนท์ |
| [getFont()](#getFont--) | คืนค่าแบบอักษรหัวข้อของย่อหน้า |
| [getHeight()](#getHeight--) | คืนค่าความสูงของหัวข้อในย่อหน้า |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | คืนค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อเลขลำดับ |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | คืนค่าสไตล์ของหัวข้อเลขลำดับ |
| [isBulletHardColor()](#isBulletHardColor--) | ตรวจสอบว่าหัวข้อมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า |
| [isBulletHardFont()](#isBulletHardFont--) | ตรวจสอบว่าหัวข้อมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า |
| [getPicture()](#getPicture--) | คืนค่าภาพที่ใช้เป็นหัวข้อในย่อหน้า |
| [getFillFormat()](#getFillFormat--) | คืนค่าแบบฟอร์มการเติมสีของหัวข้อในย่อหน้า |

### getType() {#getType--}
```
public abstract byte getType()
```

คืนค่าประเภทหัวข้อของย่อหน้า. อ่านอย่างเดียว [BulletType](../../com.aspose.slides/bullettype).

**คืนค่า:**  
byte

### getChar() {#getChar--}
```
public abstract char getChar()
```

คืนค่าตัวอักษรหัวข้อของย่อหน้า. อ่านอย่างเดียว char.

**คืนค่า:**  
char

### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

คืนค่าค่าหัวข้อที่แท้จริงสำหรับย่อหน้าพาเรนท์. อ่านอย่างเดียว String.

**คืนค่า:**  
java.lang.String

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

คืนค่าแบบอักษรหัวข้อของย่อหน้า. อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

คืนค่าความสูงของหัวข้อในย่อหน้า. อ่านอย่างเดียว float.

**คืนค่า:**  
float

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

คืนค่าตัวเลขแรกที่ใช้สำหรับกลุ่มหัวข้อเลขลำดับ. อ่านอย่างเดียว short.

**คืนค่า:**  
short

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

คืนค่าสไตล์ของหัวข้อเลขลำดับ. อ่านอย่างเดียว [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**คืนค่า:**  
byte

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

ตรวจสอบว่าหัวข้อมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. คืนค่า **true** หากหัวข้อมีสีของตนเองและ **false** หากหัวข้อสืบทอดสีจากส่วนแรกของย่อหน้า. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

ตรวจสอบว่าหัวข้อมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า. คืนค่า **true** หากหัวข้อมีแบบอักษรของตนเองและ **true** หากหัวข้อสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

คืนค่าภาพที่ใช้เป็นหัวข้อในย่อหน้า. อ่านอย่างเดียว [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**คืนค่า:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

คืนค่าแบบฟอร์มการเติมสีของหัวข้อในย่อหน้า. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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

**คืนค่า:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)