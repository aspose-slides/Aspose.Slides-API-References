---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /vi/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Lớp này chứa các thuộc tính định dạng đoạn văn. Không giống như [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

--------------------

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được xác định cho đoạn văn cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để nhận các giá trị tham số định dạng có hiệu lực bao gồm cả được kế thừa, bạn cần sử dụng phương thức [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) trả về một thể hiện [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBullet()](#getBullet--) | Trả về định dạng bullet của đoạn văn. |
| [getDepth()](#getDepth--) | Trả về hoặc thiết lập độ sâu của đoạn văn. |
| [setDepth(short value)](#setDepth-short-) | Trả về hoặc thiết lập độ sâu của đoạn văn. |
| [getAlignment()](#getAlignment--) | Trả về hoặc thiết lập căn chỉnh văn bản trong một đoạn văn không kế thừa. |
| [setAlignment(int value)](#setAlignment-int-) | Trả về hoặc thiết lập căn chỉnh văn bản trong một đoạn văn không kế thừa. |
| [getSpaceWithin()](#getSpaceWithin--) | Trả về hoặc thiết lập khoảng cách giữa các đường cơ sở trong một đoạn văn. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Trả về hoặc thiết lập khoảng cách giữa các đường cơ sở trong một đoạn văn. |
| [getSpaceBefore()](#getSpaceBefore--) | Trả về hoặc thiết lập khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Trả về hoặc thiết lập khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. |
| [getSpaceAfter()](#getSpaceAfter--) | Trả về hoặc thiết lập khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Trả về hoặc thiết lập khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Xác định liệu ngắt dòng Đông Á có được sử dụng trong một đoạn văn hay không. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Xác định liệu ngắt dòng Đông Á có được sử dụng trong một đoạn văn hay không. |
| [getRightToLeft()](#getRightToLeft--) | Xác định liệu viết từ phải sang trái có được sử dụng trong một đoạn văn hay không. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Xác định liệu viết từ phải sang trái có được sử dụng trong một đoạn văn hay không. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Xác định liệu ngắt dòng Latin có được sử dụng trong một đoạn văn hay không. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Xác định liệu ngắt dòng Latin có được sử dụng trong một đoạn văn hay không. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Xác định liệu dấu câu treo có được sử dụng trong một đoạn văn hay không. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Xác định liệu dấu câu treo có được sử dụng trong một đoạn văn hay không. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc thiết lập lề trái trong một đoạn văn không kế thừa. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Trả về hoặc thiết lập lề trái trong một đoạn văn không kế thừa. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc thiết lập lề phải trong một đoạn văn không kế thừa. |
| [setMarginRight(float value)](#setMarginRight-float-) | Trả về hoặc thiết lập lề phải trong một đoạn văn không kế thừa. |
| [getIndent()](#getIndent--) | Trả về hoặc thiết lập thụt dòng đầu tiên / thụt treo của đoạn văn không kế thừa. |
| [setIndent(float value)](#setIndent-float-) | Trả về hoặc thiết lập thụt dòng đầu tiên / thụt treo của đoạn văn không kế thừa. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. |
| [getTabs()](#getTabs--) | Trả về tab của một đoạn văn. |
| [getFontAlignment()](#getFontAlignment--) | Trả về hoặc thiết lập căn chỉnh phông chữ trong một đoạn văn không kế thừa. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Trả về hoặc thiết lập căn chỉnh phông chữ trong một đoạn văn không kế thừa. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Trả về định dạng phần mặc định của một đoạn văn. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng đoạn văn có hiệu lực với việc áp dụng kế thừa. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Trả về định dạng bullet của đoạn văn. Chỉ đọc [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Trả về:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Trả về hoặc thiết lập độ sâu của đoạn văn. Giá trị 0 có nghĩa là giá trị không xác định. Đọc/ghi short.

**Trả về:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Trả về hoặc thiết lập độ sâu của đoạn văn. Giá trị 0 có nghĩa là giá trị không xác định. Đọc/ghi short.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Trả về hoặc thiết lập căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [TextAlignment](../../com.aspose.slides/textalignment).

**Trả về:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Trả về hoặc thiết lập căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [TextAlignment](../../com.aspose.slides/textalignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Trả về hoặc thiết lập khoảng cách giữa các đường cơ sở trong một đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm - kích thước tính bằng điểm. Không áp dụng kế thừa. Đọc/ghi float.

**Trả về:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Trả về hoặc thiết lập khoảng cách giữa các đường cơ sở trong một đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm - kích thước tính bằng điểm. Không áp dụng kế thừa. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Trả về hoặc thiết lập khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương chỉ tỷ lệ phần trăm của kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi float.

**Trả về:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Trả về hoặc thiết lập khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương chỉ tỷ lệ phần trăm của kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Trả về hoặc thiết lập khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương chỉ tỷ lệ phần trăm của kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi float.

**Trả về:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Trả về hoặc thiết lập khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương chỉ tỷ lệ phần trăm của kích thước phông chữ mà khoảng trắng nên có. Giá trị âm chỉ kích thước khoảng trắng bằng điểm. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Xác định liệu ngắt dòng Đông Á có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Xác định liệu ngắt dòng Đông Á có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Xác định liệu viết từ phải sang trái có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Xác định liệu viết từ phải sang trái có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Xác định liệu ngắt dòng Latin có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Xác định liệu ngắt dòng Latin có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Xác định liệu dấu câu treo có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Xác định liệu dấu câu treo có được sử dụng trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Trả về hoặc thiết lập lề trái trong một đoạn văn không kế thừa. Đọc/ghi float.

**Trả về:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Trả về hoặc thiết lập lề trái trong một đoạn văn không kế thừa. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Trả về hoặc thiết lập lề phải trong một đoạn văn không kế thừa. Đọc/ghi float.

**Trả về:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Trả về hoặc thiết lập lề phải trong một đoạn văn không kế thừa. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Trả về hoặc thiết lập thụt dòng đầu tiên / thụt treo của đoạn văn không kế thừa. Thụt treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi float.

**Trả về:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Trả về hoặc thiết lập thụt dòng đầu tiên / thụt treo của đoạn văn không kế thừa. Thụt treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. Đọc/ghi float.

**Trả về:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Trả về hoặc thiết lập kích thước tab mặc định không kế thừa. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Trả về các tab của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [ITabCollection](../../com.aspose.slides/itabcollection).

**Trả về:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Trả về hoặc thiết lập căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [FontAlignment](../../com.aspose.slides/fontalignment).

**Trả về:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Trả về hoặc thiết lập căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [FontAlignment](../../com.aspose.slides/fontalignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Trả về định dạng phần mặc định của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [IPortionFormat](../../com.aspose.slides/iportionformat).

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng đoạn văn có hiệu lực với việc áp dụng kế thừa.

**Trả về:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).