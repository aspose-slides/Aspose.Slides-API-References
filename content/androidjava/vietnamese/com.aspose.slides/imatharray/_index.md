---
title: IMathArray
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định một mảng dọc của các phương trình hoặc bất kỳ đối tượng toán học nào
type: docs
url: /vi/com.aspose.slides/imatharray/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Xác định một mảng dọc của các phương trình hoặc bất kỳ đối tượng toán học nào

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Phương thức

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Tập hợp các mục của mảng |
| [getBaseJustification()](#getBaseJustification--) | Xác định sự căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với dưới, trên hoặc trung tâm của đối tượng mảng. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Xác định sự căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với dưới, trên hoặc trung tâm của đối tượng mảng. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution Khi đúng, mảng được căn theo chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution Khi đúng, mảng được căn theo chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution Khi đúng, nội dung của mảng được căn theo chiều rộng tối đa của đối tượng mảng. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution Khi đúng, nội dung của mảng được căn theo chiều rộng tối đa của đối tượng mảng. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Kiểu khoảng cách dọc giữa các phần tử của mảng |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Kiểu khoảng cách dọc giữa các phần tử của mảng |
| [getRowSpacing()](#getRowSpacing--) | Khoảng cách giữa các hàng của một mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp đó đơn vị đo là điểm hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Khoảng cách giữa các hàng của một mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp đó đơn vị đo là điểm hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract int getBaseJustification()
```

Xác định sự căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với dưới, trên hoặc trung tâm của đối tượng mảng. Giá trị mặc định: Center

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
public abstract void setBaseJustification(int value)
```

Xác định sự căn chỉnh của mảng so với văn bản xung quanh. Văn bản bên ngoài mảng có thể được căn chỉnh với dưới, trên hoặc trung tâm của đối tượng mảng. Giá trị mặc định: Center

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
public abstract boolean getMaximumDistribution()
```

Maximum Distribution Khi đúng, mảng được căn theo chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.).

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
public abstract void setMaximumDistribution(boolean value)
```

Maximum Distribution Khi đúng, mảng được căn theo chiều rộng tối đa của phần tử chứa (trang, cột, ô, v.v.).

--------------------

> ```
> Example:
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
public abstract boolean getObjectDistribution()
```

Object Distribution Khi đúng, nội dung của mảng được căn theo chiều rộng tối đa của đối tượng mảng.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Trả về:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Object Distribution Khi đúng, nội dung của mảng được căn theo chiều rộng tối đa của đối tượng mảng.

--------------------

> ```
> Example:
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
public abstract int getRowSpacingRule()
```

Kiểu khoảng cách dọc giữa các phần tử của mảng

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
public abstract void setRowSpacingRule(int value)
```

Kiểu khoảng cách dọc giữa các phần tử của mảng

--------------------

> ```
> Example:
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
public abstract long getRowSpacing()
```

Khoảng cách giữa các hàng của một mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp đó đơn vị đo là điểm hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Trả về:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Khoảng cách giữa các hàng của một mảng. Nó chỉ được sử dụng khi RowSpacingRule được đặt thành 3, trong trường hợp đó đơn vị đo là điểm hoặc Multiple trong trường hợp đơn vị đo là nửa dòng. Mặc định: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |