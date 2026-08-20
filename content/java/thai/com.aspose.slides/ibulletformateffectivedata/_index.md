---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /th/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

อ็อบเจ็กต์ไม่เปลี่ยนแปลงที่บรรจุคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้าที่มีผล

--------------------

อินเทอร์เฟซนี้ถูกใช้เป็นส่วนหนึ่งของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | ส่งคืนประเภทหัวข้อย่อยของย่อหน้า |
| [getChar()](#getChar--) | ส่งคืนอักขระหัวข้อย่อยของย่อหน้า |
| [getActualBulletValue()](#getActualBulletValue--) | ส่งคืนค่าหัวข้อย่อยที่ใช้งานจริงสำหรับย่อหน้าพาเรนท์ |
| [getFont()](#getFont--) | ส่งคืนแบบอักษรหัวข้อย่อยของย่อหน้า |
| [getHeight()](#getHeight--) | ส่งคืนความสูงของหัวข้อย่อยของย่อหน้า |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | ส่งคืนหมายเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลข |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | ส่งคืนสไตล์ของหัวข้อย่อยแบบลำดับเลข |
| [isBulletHardColor()](#isBulletHardColor--) | ตรวจสอบว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า |
| [isBulletHardFont()](#isBulletHardFont--) | ตรวจสอบว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า |
| [getPicture()](#getPicture--) | ส่งคืนรูปภาพที่ใช้เป็นหัวข้อย่อยในย่อหน้า |
| [getFillFormat()](#getFillFormat--) | ส่งคืนรูปแบบการเติมสีของหัวข้อย่อยในย่อหน้า |
### getType() {#getType--}
```
public abstract byte getType()
```

ส่งคืนประเภทหัวข้อย่อยของย่อหน้า อ่านอย่างเดียว [BulletType](../../com.aspose.slides/bullettype).

**คืนค่า:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

ส่งคืนอักขระหัวข้อย่อยของย่อหน้า อ่านอย่างเดียว char.

**คืนค่า:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

ส่งคืนค่าหัวข้อย่อยที่ใช้งานจริงสำหรับย่อหน้าพาเรนท์ อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

ส่งคืนแบบอักษรหัวข้อย่อยของย่อหน้า อ่านอย่างเดียว [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

ส่งคืนความสูงของหัวข้อย่อยของย่อหน้า อ่านอย่างเดียว float.

**คืนค่า:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

ส่งคืนหมายเลขแรกที่ใช้สำหรับกลุ่มหัวข้อย่อยแบบลำดับเลข อ่านอย่างเดียว short.

**คืนค่า:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

ส่งคืนสไตล์ของหัวข้อย่อยแบบลำดับเลข อ่านอย่างเดียว [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**คืนค่า:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

ตรวจสอบว่าหัวข้อย่อยมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า ส่งคืน **true** หากหัวข้อย่อยมีสีของตนเองและ **false** หากหัวข้อย่อยสืบทอดสีจากส่วนแรกของย่อหน้า อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

ตรวจสอบว่าหัวข้อย่อยมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า ส่งคืน **true** หากหัวข้อย่อยมีแบบอักษรของตนเองและ **true** หากหัวข้อย่อยสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

ส่งคืนรูปภาพที่ใช้เป็นหัวข้อย่อยในย่อหน้า อ่านอย่างเดียว [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**คืนค่า:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

ส่งคืนรูปแบบการเติมสีของหัวข้อย่อยในย่อหน้า อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // สมมติว่า shape แรกบนสไลด์แรกเป็น AutoShape ที่มีข้อความ...
>      // แสดงข้อมูลเกี่ยวกับหัวข้อย่อยของย่อความข้อความ
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