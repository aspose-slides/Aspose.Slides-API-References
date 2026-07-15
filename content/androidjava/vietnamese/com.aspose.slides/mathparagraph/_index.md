---
title: MathParagraph
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đoạn văn toán học là một bộ chứa cho các khối toán học IMathBlock
type: docs
url: /vi/com.aspose.slides/mathparagraph/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Đoạn văn toán học là một bộ chứa cho các khối toán học (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Khởi tạo một thể hiện mới của lớp MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Khởi tạo một thể hiện mới của lớp MathParagraph. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getJustification()](#getJustification--) | Giá trị mặc định của Paragraph Justification: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Giá trị mặc định của Paragraph Justification: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Trả về đối tượng Parent_Immediate. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy mục tại chỉ mục được chỉ định. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Lấy mục tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Thêm IMathBlock vào cuối bộ sưu tập. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Xác định chỉ mục của một IMathBlock cụ thể trong bộ sưu tập. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Chèn IMathBlock vào bộ sưu tập tại chỉ mục được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa một mục tại chỉ mục được chỉ định trong bộ sưu tập. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Lưu nội dung của [MathParagraph](../../com.aspose.slides/mathparagraph) này dưới dạng MathML |
| [toLatex()](#toLatex--) | Lấy phương trình toán học ở định dạng LaTeX |

### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

Khởi tạo một thể hiện mới của lớp MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```

Khởi tạo một thể hiện mới của lớp MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

Giá trị mặc định của Paragraph Justification: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Trả về:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

Giá trị mặc định của Paragraph Justification: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. Chỉ-đọc int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

Lấy mục tại chỉ mục được chỉ định. Chỉ-đọc [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần lấy |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Khối của một văn bản toán học.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

Lấy mục tại chỉ mục được chỉ định. Chỉ-đọc [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần lấy |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Khối của một văn bản toán học. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

Thêm IMathBlock vào cuối bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Khối toán học sẽ được thêm vào cuối bộ sưu tập |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Đối tượng cần xóa khỏi bộ sưu tập. |

**Trả về:**
boolean - true nếu mathBlock được xóa thành công khỏi bộ sưu tập; ngược lại, false. Phương thức này cũng trả về false nếu không tìm thấy mathBlock trong bộ sưu tập gốc.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Đối tượng cần tìm trong bộ sưu tập. |

**Trả về:**
boolean - true nếu mathBlock được tìm thấy trong bộ sưu tập; ngược lại, false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

Xác định chỉ mục của một IMathBlock cụ thể trong bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Mục cần tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục của mathBlock nếu tìm thấy trong bộ sưu tập; ngược lại, -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

Chèn IMathBlock vào bộ sưu tập tại chỉ mục được chỉ định.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần lấy |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock cần chèn. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một mục tại chỉ mục được chỉ định trong bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần xóa. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**Trả về:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Lưu nội dung của [MathParagraph](../../com.aspose.slides/mathparagraph) này dưới dạng MathML

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |

### toLatex() {#toLatex--}
```
public final String toLatex()
```

Lấy phương trình toán học ở định dạng LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Trả về:**
java.lang.String