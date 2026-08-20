---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /vi/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Đại diện cho các thuộc tính định dạng dấu đầu dòng của đoạn văn.

## Phương thức

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Trả về hoặc đặt kiểu dấu đầu dòng của một đoạn văn không kế thừa. |
| [setType(byte value)](#setType-byte-) | Trả về hoặc đặt kiểu dấu đầu dòng của một đoạn văn không kế thừa. |
| [getChar()](#getChar--) | Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa. |
| [setChar(char value)](#setChar-char-) | Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa. |
| [getFont()](#getFont--) | Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa. |
| [getHeight()](#getHeight--) | Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa. |
| [setHeight(float value)](#setHeight-float-) | Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa. |
| [getColor()](#getColor--) | Trả về định dạng màu của dấu đầu dòng của một đoạn văn không kế thừa. |
| [getPicture()](#getPicture--) | Trả về hình ảnh được sử dụng làm dấu đầu dòng trong một đoạn văn không kế thừa. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Trả về hoặc đặt số đầu tiên được dùng cho nhóm dấu đầu dòng có số đánh số không kế thừa. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Trả về hoặc đặt số đầu tiên được dùng cho nhóm dấu đầu dòng có số đánh số không kế thừa. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Trả về hoặc đặt kiểu dáng của dấu đầu dòng có số đánh số không kế thừa. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Trả về hoặc đặt kiểu dáng của dấu đầu dòng có số đánh số không kế thừa. |
| [isBulletHardColor()](#isBulletHardColor--) | Xác định xem dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Xác định xem dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [isBulletHardFont()](#isBulletHardFont--) | Xác định xem dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Xác định xem dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Đặt các dịch chuyển mặc định không bằng không cho Indent và MarginLeft hiệu quả của đoạn văn khi bật dấu đầu dòng (giống PowerPoint khi bật dấu đầu dòng/đánh số). |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng dấu đầu dòng hiệu quả với việc kế thừa đã được áp dụng. |

### getType() {#getType--}
```
public abstract byte getType()
```

Trả về hoặc đặt kiểu dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi [BulletType](../../com.aspose.slides/bullettype).

**Giá trị trả về:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Trả về hoặc đặt kiểu dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi [BulletType](../../com.aspose.slides/bullettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi char.

**Giá trị trả về:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi char.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Giá trị trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa. Giá trị Float.NaN xác định rằng dấu đầu dòng kế thừa chiều cao từ phần đầu tiên trong đoạn văn. Đọc/ghi float.

**Giá trị trả về:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa. Giá trị Float.NaN xác định rằng dấu đầu dòng kế thừa chiều cao từ phần đầu tiên trong đoạn văn. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Trả về định dạng màu của dấu đầu dòng của một đoạn văn không kế thừa. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Giá trị trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Trả về hình ảnh được sử dụng làm dấu đầu dòng trong một đoạn văn không kế thừa. Chỉ đọc [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Giá trị trả về:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Trả về hoặc đặt số đầu tiên được dùng cho nhóm dấu đầu dòng có số đánh số không kế thừa. Đọc/ghi short.

**Giá trị trả về:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Trả về hoặc đặt số đầu tiên được dùng cho nhóm dấu đầu dòng có số đánh số không kế thừa. Đọc/ghi short.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Trả về hoặc đặt kiểu dáng của một dấu đầu dòng có số đánh số không kế thừa. Đọc/ghi [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Giá trị trả về:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Trả về hoặc đặt kiểu dáng của một dấu đầu dòng có số đánh số không kế thừa. Đọc/ghi [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Xác định xem dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool\#True** nếu dấu đầu dòng có màu riêng và **NullableBool\#False** nếu dấu đầu dòng kế thừa màu từ phần đầu tiên trong đoạn văn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Giá trị trả về:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Xác định xem dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool\#True** nếu dấu đầu dòng có màu riêng và **NullableBool\#False** nếu dấu đầu dòng kế thừa màu từ phần đầu tiên trong đoạn văn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Xác định xem dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool\#True** nếu dấu đầu dòng có phông chữ riêng và **NullableBool\#False** nếu dấu đầu dòng kế thừa phông chữ từ phần đầu tiên trong đoạn văn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Giá trị trả về:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Xác định xem dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn. **NullableBool\#True** nếu dấu đầu dòng có phông chữ riêng và **NullableBool\#False** nếu dấu đầu dòng kế thừa phông chữ từ phần đầu tiên trong đoạn văn. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Đặt các dịch chuyển mặc định không bằng không cho Indent và MarginLeft hiệu quả của đoạn văn khi bật dấu đầu dòng (giống PowerPoint khi bật dấu đầu dòng/đánh số). Nếu tắt dấu đầu dòng thì chỉ đặt lại Indent và MarginLeft của đoạn văn (giống PowerPoint khi tắt dấu đầu dòng/đánh số). Các dịch chuyển Indent được áp dụng dựa trên ngữ cảnh dấu đầu dòng hiện tại — IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các dịch chuyển không bằng không được áp dụng cho Indent và MarginLeft hiệu quả của đoạn văn hiện tại (để giá trị kết quả là giá trị cục bộ).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng dấu đầu dòng hiệu quả với việc kế thừa đã được áp dụng.

--------------------

> ```
> Ví dụ này minh họa cách lấy một số thuộc tính định dạng dấu đầu dòng hiệu quả.
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


**Giá trị trả về:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).