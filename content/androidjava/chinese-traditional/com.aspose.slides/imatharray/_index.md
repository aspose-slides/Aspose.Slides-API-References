---
title: IMathArray
second_title: Aspose.Slides for Android via Java API 參考文件
description: 指定一個垂直的等式或任何數學物件陣列
type: docs
url: /zh-hant/com.aspose.slides/imatharray/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

指定一個垂直的等式或任何數學物件陣列

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getArguments()](#getArguments--) | 陣列項目的集合 |
| [getBaseJustification()](#getBaseJustification--) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution：當為 true 時，陣列會依據包含元素（頁面、欄、儲存格等）的最大寬度進行間距。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution：當為 true 時，陣列會依據包含元素（頁面、欄、儲存格等）的最大寬度進行間距。 |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution：當為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution：當為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 陣列元素之間垂直間距的類型 |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 陣列元素之間垂直間距的類型 |
| [getRowSpacing()](#getRowSpacing--) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若設定為 Exactly，則度量單位為點；若設定為 Multiple，則度量單位為半行。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若設定為 Exactly，則度量單位為點；若設定為 Multiple，則度量單位為半行。 |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

陣列項目的集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**傳回：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。預設值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**傳回：**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

指定陣列相對於周圍文字的對齊方式。陣列外的文字可以與陣列物件的底部、頂部或中心對齊。預設值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Maximum Distribution：當為 true 時，陣列會依據包含元素（頁面、欄、儲存格等）的最大寬度進行間距。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**傳回：**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Maximum Distribution：當為 true 時，陣列會依據包含元素（頁面、欄、儲存格等）的最大寬度進行間距。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Object Distribution：當為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**傳回：**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Object Distribution：當為 true 時，陣列的內容會依據陣列物件的最大寬度進行間距。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

陣列元素之間垂直間距的類型

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**傳回：**
int

### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

陣列元素之間垂直間距的類型

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若設定為 Exactly，則度量單位為點；若設定為 Multiple，則度量單位為半行。預設值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**傳回：**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

陣列列之間的間距。僅在 RowSpacingRule 設為 3 時使用，若設定為 Exactly，則度量單位為點；若設定為 Multiple，則度量單位為半行。預設值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |