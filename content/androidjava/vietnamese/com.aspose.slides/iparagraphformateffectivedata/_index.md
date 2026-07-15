---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng bất biến chứa các thuộc tính định dạng đoạn văn hiệu quả.
type: docs
url: /vi/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính định dạng đoạn văn hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [IParagraphFormat](../../com.aspose.slides/iparagraphformat) để trả về các giá trị định dạng hiệu quả có áp dụng kế thừa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBullet()](#getBullet--) | Trả về định dạng dấu đầu dòng của một đoạn văn. |
| [getDepth()](#getDepth--) | Trả về độ sâu của một đoạn văn. |
| [getAlignment()](#getAlignment--) | Trả về căn lề văn bản trong một đoạn văn. |
| [getSpaceWithin()](#getSpaceWithin--) | Trả về khoảng cách giữa các dòng cơ sở trong một đoạn văn. |
| [getSpaceBefore()](#getSpaceBefore--) | Trả về khoảng cách trước dòng đầu tiên trong một đoạn văn. |
| [getSpaceAfter()](#getSpaceAfter--) | Trả về khoảng cách sau dòng cuối cùng trong một đoạn văn. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Xác định xem có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. |
| [getRightToLeft()](#getRightToLeft--) | Xác định xem có sử dụng viết từ phải sang trái trong một đoạn văn hay không. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Xác định xem có sử dụng ngắt dòng Latin trong một đoạn văn hay không. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Xác định xem có sử dụng dấu câu treo trong một đoạn văn hay không. |
| [getMarginLeft()](#getMarginLeft--) | Trả về lề trái trong một đoạn văn. |
| [getMarginRight()](#getMarginRight--) | Trả về lề phải trong một đoạn văn. |
| [getIndent()](#getIndent--) | Trả về thụt lề dòng đầu / thụt lề treo của đoạn văn. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Trả về kích thước tab mặc định. |
| [getTabs()](#getTabs--) | Trả về các tabulation của một đoạn văn. |
| [getFontAlignment()](#getFontAlignment--) | Trả về căn chỉnh phông chữ trong một đoạn văn. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Trả về định dạng phần mặc định của một đoạn văn. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Trả về định dạng dấu đầu dòng của một đoạn văn. Chỉ đọc [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Trả về:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Trả về độ sâu của một đoạn văn. Chỉ đọc short.

**Trả về:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Trả về căn lề văn bản trong một đoạn văn. Chỉ đọc [TextAlignment](../../com.aspose.slides/textalignment).

**Trả về:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Trả về khoảng cách giữa các dòng cơ sở trong một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Trả về khoảng cách trước dòng đầu tiên trong một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Trả về khoảng cách sau dòng cuối cùng trong một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Xác định xem có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Xác định xem có sử dụng viết từ phải sang trái trong một đoạn văn hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Xác định xem có sử dụng ngắt dòng Latin trong một đoạn văn hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Xác định xem có sử dụng dấu câu treo trong một đoạn văn hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Trả về lề trái trong một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Trả về lề phải trong một đoạn văn. Chỉ đọc float.

**Trả về:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Trả về thụt lề dòng đầu / thụt lề treo của đoạn văn. Thụt lề treo có thể được định nghĩa bằng giá trị âm. Chỉ đọc float.

**Trả về:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Trả về kích thước tab mặc định. Chỉ đọc float.

**Trả về:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Trả về các tabulation của một đoạn văn. Chỉ đọc ITabEffectiveData[].

**Trả về:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Trả về căn chỉnh phông chữ trong một đoạn văn. Chỉ đọc [FontAlignment](../../com.aspose.slides/fontalignment).

**Trả về:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Trả về định dạng phần mặc định của một đoạn văn. Chỉ đọc [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Trả về:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)