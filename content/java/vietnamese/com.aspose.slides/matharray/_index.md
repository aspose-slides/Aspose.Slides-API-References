---
title: MathArray
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định một mảng dọc các phương trình hoặc bất kỳ đối tượng toán học nào
type: docs
url: /vi/com.aspose.slides/matharray/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Xác định một mảng dọc các phương trình hoặc bất kỳ đối tượng toán học nào

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
```
## Hàm tạo

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Tạo một mảng toán học và đặt phần tử được chỉ định vào trong nó |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Tạo một mảng toán học và đặt các phần tử được chỉ định vào trong nó |
## Phương thức

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Tập hợp các mục của mảng |
| [getBaseJustification()](#getBaseJustification--) | Xác định căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, đầu hoặc trung tâm của đối tượng mảng. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, đầu hoặc trung tâm của đối tượng mảng. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Phân phối tối đa Khi true, mảng được căn rộng tới chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Phân phối tối đa Khi true, mảng được căn rộng tới chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [getObjectDistribution()](#getObjectDistribution--) | Phân phối đối tượng Khi true, nội dung của mảng được căn rộng tới chiều rộng tối đa của đối tượng mảng. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Phân phối đối tượng Khi true, nội dung của mảng được căn rộng tới chiều rộng tối đa của đối tượng mảng. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Kiểu khoảng cách theo chiều dọc giữa các phần tử của mảng Mặc định: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Kiểu khoảng cách theo chiều dọc giữa các phần tử của mảng Mặc định: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Khoảng cách giữa các hàng của mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Khoảng cách giữa các hàng của mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0 |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Tạo một mảng toán học và đặt phần tử được chỉ định vào trong nó

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

Tạo một mảng toán học và đặt các phần tử được chỉ định vào trong nó

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

**Giá trị trả về:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Xác định căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, đầu hoặc trung tâm của đối tượng mảng. Mặc định: Center

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Giá trị trả về:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Xác định căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với đáy, đầu hoặc trung tâm của đối tượng mảng. Mặc định: Center

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

Phân phối tối đa Khi true, mảng được căn rộng tới chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.).

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Giá trị trả về:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Phân phối tối đa Khi true, mảng được căn rộng tới chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.).

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

Phân phối đối tượng Khi true, nội dung của mảng được căn rộng tới chiều rộng tối đa của đối tượng mảng.

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Giá trị trả về:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Phân phối đối tượng Khi true, nội dung của mảng được căn rộng tới chiều rộng tối đa của đối tượng mảng.

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

Kiểu khoảng cách theo chiều dọc giữa các phần tử của mảng Mặc định: SingleLineGap

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Giá trị trả về:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Kiểu khoảng cách theo chiều dọc giữa các phần tử của mảng Mặc định: SingleLineGap

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

Khoảng cách giữa các hàng của mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

--------------------

> ```
> Ví dụ:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Giá trị trả về:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Khoảng cách giữa các hàng của mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp này đơn vị đo là điểm, hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

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

**Giá trị trả về:**
com.aspose.slides.IMathElement[]