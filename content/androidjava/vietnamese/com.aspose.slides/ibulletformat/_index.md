---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn các thuộc tính định dạng bullet của đoạn văn.
type: docs
url: /vi/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Biểu diễn các thuộc tính định dạng bullet của đoạn văn.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về hoặc đặt loại bullet của một đoạn văn không kế thừa. |
| [setType(byte value)](#setType-byte-) | Trả về hoặc đặt loại bullet của một đoạn văn không kế thừa. |
| [getChar()](#getChar--) | Trả về hoặc đặt ký tự bullet của một đoạn văn không kế thừa. |
| [setChar(char value)](#setChar-char-) | Trả về hoặc đặt ký tự bullet của một đoạn văn không kế thừa. |
| [getFont()](#getFont--) | Trả về hoặc đặt phông chữ bullet của một đoạn văn không kế thừa. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông chữ bullet của một đoạn văn không kế thừa. |
| [getHeight()](#getHeight--) | Trả về hoặc đặt chiều cao bullet của một đoạn văn không kế thừa. |
| [setHeight(float value)](#setHeight-float-) | Trả về hoặc đặt chiều cao bullet của một đoạn văn không kế thừa. |
| [getColor()](#getColor--) | Trả về định dạng màu của bullet trong một đoạn văn không kế thừa. |
| [getPicture()](#getPicture--) | Trả về hình ảnh được sử dụng làm bullet trong một đoạn văn không kế thừa. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Trả về hoặc đặt số đầu tiên được dùng cho nhóm các bullet có số thứ tự không kế thừa. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Trả về hoặc đặt số đầu tiên được dùng cho nhóm các bullet có số thứ tự không kế thừa. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Trả về hoặc đặt kiểu của bullet có số thứ tự không kế thừa. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Trả về hoặc đặt kiểu của bullet có số thứ tự không kế thừa. |
| [isBulletHardColor()](#isBulletHardColor--) | Xác định liệu bullet có màu riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Xác định liệu bullet có màu riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. |
| [isBulletHardFont()](#isBulletHardFont--) | Xác định liệu bullet có phông chữ riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Xác định liệu bullet có phông chữ riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Đặt các độ dịch khác không-zero mặc định cho Indent và MarginLeft thực tế của đoạn khi bullet được bật (giống như PowerPoint làm khi bật bullet/đánh số). |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng bullet thực tế với kế thừa đã được áp dụng. |
### getType() {#getType--}
```
public abstract byte getType()
```


Trả về hoặc đặt loại bullet của một đoạn văn không kế thừa. Đọc/ghi [BulletType](../../com.aspose.slides/bullettype).

**Trả về:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Trả về hoặc đặt loại bullet của một đoạn văn không kế thừa. Đọc/ghi [BulletType](../../com.aspose.slides/bullettype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Trả về hoặc đặt ký tự bullet của một đoạn văn không kế thừa. Đọc/ghi char.

**Trả về:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Trả về hoặc đặt ký tự bullet của một đoạn văn không kế thừa. Đọc/ghi char.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Trả về hoặc đặt phông chữ bullet của một đoạn văn không kế thừa. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Trả về hoặc đặt phông chữ bullet của một đoạn văn không kế thừa. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Trả về hoặc đặt chiều cao bullet của một đoạn văn không kế thừa. Giá trị Float.NaN xác định bullet kế thừa chiều cao từ phần đầu tiên trong đoạn. Đọc/ghi float.

**Trả về:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Trả về hoặc đặt chiều cao bullet của một đoạn văn không kế thừa. Giá trị Float.NaN xác định bullet kế thừa chiều cao từ phần đầu tiên trong đoạn. Đọc/ghi float.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Trả về định dạng màu của bullet trong một đoạn văn không kế thừa. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Trả về hình ảnh được sử dụng làm bullet trong một đoạn văn không kế thừa. Chỉ đọc [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Trả về:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Trả về hoặc đặt số đầu tiên được dùng cho nhóm các bullet có số thứ tự không kế thừa. Đọc/ghi short.

**Trả về:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Trả về hoặc đặt số đầu tiên được dùng cho nhóm các bullet có số thứ tự không kế thừa. Đọc/ghi short.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Trả về hoặc đặt kiểu của bullet có số thứ tự không kế thừa. Đọc/ghi [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Trả về:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Trả về hoặc đặt kiểu của bullet có số thứ tự không kế thừa. Đọc/ghi [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Xác định liệu bullet có màu riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool#True** nếu bullet có màu riêng và **NullableBool#False** nếu bullet kế thừa màu từ phần đầu tiên trong đoạn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Xác định liệu bullet có màu riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool#True** nếu bullet có màu riêng và **NullableBool#False** nếu bullet kế thừa màu từ phần đầu tiên trong đoạn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Xác định liệu bullet có phông chữ riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool#True** nếu bullet có phông chữ riêng và **NullableBool#False** nếu bullet kế thừa phông chữ từ phần đầu tiên trong đoạn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Xác định liệu bullet có phông chữ riêng hoặc kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool#True** nếu bullet có phông chữ riêng và **NullableBool#False** nếu bullet kế thừa phông chữ từ phần đầu tiên trong đoạn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Đặt các độ dịch khác không-zero mặc định cho Indent và MarginLeft thực tế của đoạn khi bullet được bật (giống như PowerPoint làm khi bật bullet/đánh số). Nếu bullet bị tắt thì chỉ đặt lại Indent và MarginLeft của đoạn (giống như PowerPoint làm khi tắt bullet/đánh số). Các độ dịch Indent được áp dụng dựa trên ngữ cảnh bullet hiện tại – IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các độ dịch không-zero được áp dụng cho Indent và MarginLeft thực tế của đoạn hiện tại (kết quả là các giá trị trở thành giá trị cục bộ).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng bullet thực tế với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).