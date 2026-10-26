---
title: ParagraphFormat
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Lớp này chứa các thuộc tính định dạng đoạn văn.
type: docs
url: /vi/com.aspose.slides/paragraphformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Lớp này chứa các thuộc tính định dạng đoạn văn. Khác với [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

--------------------

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng đoạn văn được xác định cho đoạn văn cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, vì vậy trong phần lớn trường hợp bạn sẽ nhận được các giá trị có nghĩa là “không xác định”.

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả đã kế thừa, bạn cần sử dụng phương thức [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) trả về một thể hiện [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Khởi tạo một thể hiện mới của lớp [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBullet()](#getBullet--) | Trả về định dạng dấu đầu dòng của đoạn văn. |
| [getDepth()](#getDepth--) | Trả về hoặc đặt độ sâu của đoạn văn. |
| [setDepth(short value)](#setDepth-short-) | Trả về hoặc đặt độ sâu của đoạn văn. |
| [getAlignment()](#getAlignment--) | Trả về hoặc đặt căn chỉnh văn bản trong một đoạn văn không kế thừa. |
| [setAlignment(int value)](#setAlignment-int-) | Trả về hoặc đặt căn chỉnh văn bản trong một đoạn văn không kế thừa. |
| [getSpaceWithin()](#getSpaceWithin--) | Trả về hoặc đặt khoảng cách giữa các đường cơ sở trong một đoạn văn. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Trả về hoặc đặt khoảng cách giữa các đường cơ sở trong một đoạn văn. |
| [getSpaceBefore()](#getSpaceBefore--) | Trả về hoặc đặt khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Trả về hoặc đặt khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. |
| [getSpaceAfter()](#getSpaceAfter--) | Trả về hoặc đặt khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Trả về hoặc đặt khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. |
| [getRightToLeft()](#getRightToLeft--) | Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Xác định liệu có sử dụng ngắt dòng La-tinh trong một đoạn văn hay không. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Xác định liệu có sử dụng ngắt dòng La-tinh trong một đoạn văn hay không. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái trong một đoạn văn không kế thừa. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Trả về hoặc đặt lề trái trong một đoạn văn không kế thừa. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải trong một đoạn văn không kế thừa. |
| [setMarginRight(float value)](#setMarginRight-float-) | Trả về hoặc đặt lề phải trong một đoạn văn không kế thừa. |
| [getIndent()](#getIndent--) | Trả về hoặc đặt Độ thụt dòng đầu/Độ thụt treo của đoạn văn không kế thừa. |
| [setIndent(float value)](#setIndent-float-) | Trả về hoặc đặt Độ thụt dòng đầu/Độ thụt treo của đoạn văn không kế thừa. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Trả về hoặc đặt kích thước tab mặc định không kế thừa. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Trả về hoặc đặt kích thước tab mặc định không kế thừa. |
| [getTabs()](#getTabs--) | Trả về các tab của một đoạn văn. |
| [getFontAlignment()](#getFontAlignment--) | Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn văn không kế thừa. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn văn không kế thừa. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Trả về định dạng phần mặc định của một đoạn văn. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng đoạn văn hiệu quả với kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Khởi tạo một thể hiện mới của lớp [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Trả về định dạng dấu đầu dòng của đoạn văn. Chỉ đọc [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Returns:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Trả về hoặc đặt độ sâu của đoạn văn. Giá trị 0 có nghĩa là giá trị không xác định. Đọc/ghi  short .

**Returns:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Trả về hoặc đặt độ sâu của đoạn văn. Giá trị 0 có nghĩa là giá trị không xác định. Đọc/ghi  short .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Trả về hoặc đặt căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Tạo một đối tượng Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Truy cập slide đầu tiên
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Truy cập placeholder thứ nhất và thứ hai trong slide và ép kiểu thành AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Thay đổi văn bản trong cả hai placeholder
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Lấy đoạn văn đầu tiên của các placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Căn chỉnh đoạn văn bản vào Trung tâm
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Ghi bản trình bày dưới dạng tệp PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Trả về hoặc đặt căn chỉnh văn bản trong một đoạn văn không kế thừa. Đọc/ghi [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Tạo một đối tượng Presentation đại diện cho tệp PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Truy cập slide đầu tiên
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Truy cập placeholder thứ nhất và thứ hai trong slide và ép kiểu thành AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Thay đổi văn bản trong cả hai placeholder
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Lấy đoạn văn đầu tiên của các placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Căn chỉnh đoạn văn bản vào trung tâm
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Ghi bản trình bày dưới dạng tệp PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Trả về hoặc đặt khoảng cách giữa các đường cơ sở trong một đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm - kích thước theo điểm. Không áp dụng kế thừa. Đọc/ghi  float .

**Returns:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Trả về hoặc đặt khoảng cách giữa các đường cơ sở trong một đoạn văn. Giá trị dương có nghĩa là phần trăm, giá trị âm - kích thước theo điểm. Không áp dụng kế thừa. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Trả về hoặc đặt khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương xác định phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm xác định kích thước khoảng trắng bằng điểm. Đọc/ghi  float .

**Returns:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Trả về hoặc đặt khoảng cách trước dòng đầu tiên trong một đoạn văn không kế thừa. Giá trị dương xác định phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm xác định kích thước khoảng trắng bằng điểm. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Trả về hoặc đặt khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương xác định phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm xác định kích thước khoảng trắng bằng điểm. Đọc/ghi  float .

**Returns:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Trả về hoặc đặt khoảng cách sau dòng cuối cùng trong một đoạn văn không kế thừa. Giá trị dương xác định phần trăm kích thước phông chữ mà khoảng trắng nên có. Giá trị âm xác định kích thước khoảng trắng bằng điểm. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Xác định liệu có sử dụng ngắt dòng Đông Á trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Xác định liệu có sử dụng viết từ phải sang trái trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Xác định liệu có sử dụng ngắt dòng La-tinh trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Xác định liệu có sử dụng ngắt dòng La-tinh trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Xác định liệu có sử dụng dấu câu treo trong một đoạn văn hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Trả về hoặc đặt lề trái trong một đoạn văn không kế thừa. Đọc/ghi  float .

**Returns:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Trả về hoặc đặt lề trái trong một đoạn văn không kế thừa. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Trả về hoặc đặt lề phải trong một đoạn văn không kế thừa. Đọc/ghi  float .

**Returns:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Trả về hoặc đặt lề phải trong một đoạn văn không kế thừa. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Trả về hoặc đặt Độ thụt dòng đầu/Độ thụt treo của đoạn văn không kế thừa. Độ thụt treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi  float .

**Returns:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Trả về hoặc đặt Độ thụt dòng đầu/Độ thụt treo của đoạn văn không kế thừa. Độ thụt treo có thể được định nghĩa bằng giá trị âm. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Trả về hoặc đặt kích thước tab mặc định không kế thừa. Đọc/ghi  float .

**Returns:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Trả về hoặc đặt kích thước tab mặc định không kế thừa. Đọc/ghi  float .

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Trả về các tab của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [ITabCollection](../../com.aspose.slides/itabcollection).

**Returns:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Trả về hoặc đặt căn chỉnh phông chữ trong một đoạn văn không kế thừa. Đọc/ghi [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Trả về định dạng phần mặc định của một đoạn văn. Không áp dụng kế thừa. Chỉ đọc [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng đoạn văn hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> Ví dụ này minh họa cách lấy một số thuộc tính định dạng đoạn văn hiệu quả.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Returns:**
long