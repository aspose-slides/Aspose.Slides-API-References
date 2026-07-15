---
title: MathBlock
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Xác định một thể hiện của văn bản toán học được chứa trong một MathParagraph và bắt đầu trên một dòng riêng.
type: docs
url: /vi/com.aspose.slides/mathblock/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Xác định một thể hiện của văn bản toán học được chứa trong một MathParagraph và bắt đầu trên một dòng riêng. Tất cả các vùng toán học, bao gồm phương trình, biểu thức, mảng các phương trình hoặc biểu thức, và công thức đều được biểu diễn bởi khối toán học.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathBlock()](#MathBlock--) | Khởi tạo một thể hiện mới của lớp MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Tạo một khối toán học mới và đặt phần tử đã chỉ định vào trong nó |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tạo một khối toán học mới và đặt các phần tử đã chỉ định vào trong nó |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Lấy số lượng các phần tử con thực tế chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy hoặc đặt IMathElement tại chỉ mục đã chỉ định. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Lấy hoặc đặt IMathElement tại chỉ mục đã chỉ định. |
| [isReadOnly()](#isReadOnly--) | Trả về false vì bộ sưu tập các phần tử con có thể được sửa đổi. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getParent_Immediate()](#getParent-Immediate--) | Trả về đối tượng Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Thêm một phần tử toán học vào cuối bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Sao chép vào mảng đã chỉ định. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Xác định chỉ mục của một phần tử toán học cụ thể trong bộ sưu tập. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Chèn một MathElement vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Nối một phần tử toán học với khối toán học này |
| [join(String mathText)](#join-java.lang.String-) | Nối một văn bản toán học với khối toán học này |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Nối một khối toán học khác với khối này |
| [delimit(char separatorCharacter)](#delimit-char-) | Phân cách các phần tử con bằng ký tự ngăn cách (không có dấu ngoặc) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc ký tự khác |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc ký tự khác và phân cách bằng ký tự ngăn cách |
| [toMathArray()](#toMathArray--) | Đặt các phần tử con vào một mảng dọc |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Lưu nội dung của [MathBlock](../../com.aspose.slides/mathblock) này dưới dạng MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Khởi tạo một thể hiện mới của lớp MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Tạo một khối toán học mới và đặt phần tử đã chỉ định vào trong nó

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử toán học để đặt vào khối |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Tạo một khối toán học mới và đặt các phần tử đã chỉ định vào trong nó

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Các phần tử toán học để đặt vào khối |

### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số lượng các phần tử con thực tế chứa trong bộ sưu tập. int chỉ đọc.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Lấy hoặc đặt IMathElement tại chỉ mục đã chỉ định.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục |

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement) - Phần tử toán học.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Lấy hoặc đặt IMathElement tại chỉ mục đã chỉ định.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục |
| value | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử toán học. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Trả về false vì bộ sưu tập các phần tử con có thể được sửa đổi.

**Trả về:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. IDOMObject chỉ đọc.

**Trả về:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Thêm một phần tử toán học vào cuối bộ sưu tập.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement sẽ được thêm vào cuối bộ sưu tập. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Đối tượng cần tìm trong bộ sưu tập. |

**Trả về:**
boolean - true nếu mục được tìm thấy trong bộ sưu tập; ngược lại, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Sao chép vào mảng đã chỉ định.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | Mảng để sao chép vào. |
| arrayIndex | int | Chỉ mục bắt đầu sao chép. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Đối tượng sẽ bị xóa khỏi bộ sưu tập. |

**Trả về:**
boolean - true nếu mục đã được xóa thành công khỏi bộ sưu tập; ngược lại, false. Phương thức này cũng trả về false nếu mục không tồn tại trong bộ sưu tập gốc.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.IEnumerator - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Xác định chỉ mục của một phần tử toán học cụ thể trong bộ sưu tập.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cần tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục của mục nếu tìm thấy trong bộ sưu tập; ngược lại, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Chèn một MathElement vào bộ sưu tập tại chỉ mục đã chỉ định.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại vị trí mà MathElement sẽ được chèn. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement sẽ được chèn. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập.

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử sẽ bị xóa. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Nối một phần tử toán học với khối toán học này

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử sẽ được nối |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Thực thể hiện tại của IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Nối một văn bản toán học với khối toán học này

--------------------

> ```
> Ví dụ:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathText | java.lang.String | Văn bản toán học sẽ được nối |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Một IMathBlock mới chứa thực thể này và đối số đã chỉ định
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Nối một khối toán học khác với khối này

--------------------

> ```
> Ví dụ:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Khối sẽ được nối |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học này sau khi nối
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Phân cách các phần tử con bằng ký tự ngăn cách (không có dấu ngoặc)

--------------------

> ```
> Ví dụ:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| separatorCharacter | char | Ký tự ngăn cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học kiểu [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc ký tự khác

--------------------

> ```
> Ví dụ:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| beginningCharacter | char | Ký tự bắt đầu (thường là dấu ngoặc trái) |
| endingCharacter | char | Ký tự kết thúc (thường là dấu ngoặc phải) |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học kiểu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm các ký tự được chỉ định làm khung
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Bao quanh các phần tử con của khối này bằng các ký tự được chỉ định như dấu ngoặc hoặc ký tự khác và phân cách bằng ký tự ngăn cách

--------------------

> ```
> Ví dụ:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| beginningCharacter | char | Ký tự bắt đầu (thường là dấu ngoặc trái) |
| endingCharacter | char | Ký tự kết thúc (thường là dấu ngoặc phải) |
| separatorCharacter | char | Ký tự ngăn cách |

**Trả về:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Phần tử toán học kiểu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) bao gồm các ký tự được chỉ định làm khung và ký tự ngăn cách
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Đặt các phần tử con vào một mảng dọc

--------------------

> ```
> Ví dụ:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Trả về:**
[IMathArray](../../com.aspose.slides/imatharray) - Thực thể mới kiểu [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Lưu nội dung của [MathBlock](../../com.aspose.slides/mathblock) này dưới dạng MathML

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |