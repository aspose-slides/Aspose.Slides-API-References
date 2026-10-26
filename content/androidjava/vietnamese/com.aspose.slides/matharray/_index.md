---
title: MathArray
second_title: Tham chiếu API Java Aspose.Slides cho Android
description: Xác định một mảng dọc chứa các phương trình hoặc bất kỳ đối tượng toán học nào
type: docs
url: /vi/com.aspose.slides/matharray/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Xác định một mảng dọc chứa các phương trình hoặc bất kỳ đối tượng toán học nào

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Tạo một mảng toán học và đặt phần tử được chỉ định vào trong đó |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tạo một mảng toán học và đặt các phần tử được chỉ định vào trong đó |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getArguments()](#getArguments--) | Tập hợp các mục của mảng |
| [getBaseJustification()](#getBaseJustification--) | Xác định cách căn chỉnh mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn với đáy, trên hoặc trung tâm của đối tượng mảng. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định cách căn chỉnh mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn với đáy, trên hoặc trung tâm của đối tượng mảng. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Phân phối tối đa Khi đúng, mảng được căn đến độ rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Phân phối tối đa Khi đúng, mảng được căn đến độ rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [getObjectDistribution()](#getObjectDistribution--) | Phân phối đối tượng Khi đúng, nội dung của mảng được căn đến độ rộng tối đa của đối tượng mảng. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Phân phối đối tượng Khi đúng, nội dung của mảng được căn đến độ rộng tối đa của đối tượng mảng. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Loại khoảng cách dọc giữa các phần tử của mảng. Mặc định: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Loại khoảng cách dọc giữa các phần tử của mảng. Mặc định: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Khoảng cách giữa các hàng của mảng. Chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Khoảng cách giữa các hàng của mảng. Chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Tạo một mảng toán học và đặt phần tử được chỉ định vào trong đó

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử để đặt vào mảng |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Tạo một mảng toán học và đặt các phần tử được chỉ định vào trong đó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Các phần tử để đặt vào mảng |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Tập hợp các mục của mảng

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Trả về:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Xác định cách căn chỉnh mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn với đáy, trên hoặc trung tâm của đối tượng mảng. Giá trị mặc định: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Trả về:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Xác định cách căn chỉnh mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn với đáy, trên hoặc trung tâm của đối tượng mảng. Giá trị mặc định: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Phân phối tối đa Khi đúng, mảng được căn đến độ rộng tối đa của phần tử chứa (trang, cột, ô, v.v.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Trả về:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Phân phối tối đa Khi đúng, mảng được căn đến độ rộng tối đa của phần tử chứa (trang, cột, ô, v.t.).

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Phân phối đối tượng Khi đúng, nội dung của mảng được căn đến độ rộng tối đa của đối tượng mảng.

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Trả về:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Phân phối đối tượng Khi đúng, nội dung của mảng được căn đến độ rộng tối đa của đối tượng mảng.

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Loại khoảng cách dọc giữa các phần tử của mảng. Mặc định: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Trả về:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Loại khoảng cách dọc giữa các phần tử của mảng. Mặc định: SingleLineGap

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Khoảng cách giữa các hàng của mảng. Chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Trả về:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Khoảng cách giữa các hàng của mảng. Chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]