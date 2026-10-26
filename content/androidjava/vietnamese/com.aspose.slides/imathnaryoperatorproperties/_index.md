---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides cho Android thông qua Java API Reference
description: Xác định các thuộc tính của IMathNaryOperator
type: docs
url: /vi/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Xác định các thuộc tính của IMathNaryOperator
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getOperator()](#getOperator--) | Ký tự toán tử Nary Ví dụ: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Ký tự toán tử Nary Ví dụ: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Vị trí của giới hạn (chỉ số và chỉ số trên) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Vị trí của giới hạn (chỉ số và chỉ số trên) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Ký tự toán tử mở rộng theo chiều dọc để phù hợp với chiều cao toán hạng |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Ký tự toán tử mở rộng theo chiều dọc để phù hợp với chiều cao toán hạng |
| [getHideSubscript()](#getHideSubscript--) | Ẩn chỉ số |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ẩn chỉ số |
| [getHideSuperscript()](#getHideSuperscript--) | Ẩn chỉ số trên |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ẩn chỉ số trên |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```

Ký tự toán tử Nary Ví dụ: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Trả về:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```

Ký tự toán tử Nary Ví dụ: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```

Vị trí của giới hạn (chỉ số và chỉ số trên)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**Trả về:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```

Vị trí của giới hạn (chỉ số và chỉ số trên)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Ký tự toán tử mở rộng theo chiều dọc để phù hợp với chiều cao toán hạng

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```


**Trả về:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Ký tự toán tử mở rộng theo chiều dọc để phù hợp với chiều cao toán hạng

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```

Ẩn chỉ số

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Trả về:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```

Ẩn chỉ số

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```

Ẩn chỉ số trên

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Trả về:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```

Ẩn chỉ số trên

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |