---
title: IMathArray
second_title: Android 用 Aspose.Slides（Java API リファレンス）
description: 方程式または任意の数学的オブジェクトの垂直配列を指定します
type: docs
url: /ja/com.aspose.slides/imatharray/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

方程式または任意の数学的オブジェクトの垂直配列を指定します

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 配列の項目の集合 |
| [getBaseJustification()](#getBaseJustification--) | 配列の配置を周囲のテキストに対して指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に合わせて配置できます。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 配列の配置を周囲のテキストに対して指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に合わせて配置できます。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | 最大分布。true の場合、配列は含む要素（ページ、列、セルなど）の最大幅まで間隔が調整されます。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 最大分布。true の場合、配列は含む要素（ページ、列、セルなど）の最大幅まで間隔が調整されます。 |
| [getObjectDistribution()](#getObjectDistribution--) | オブジェクト分布。true の場合、配列の内容は配列オブジェクトの最大幅まで間隔が調整されます。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | オブジェクト分布。true の場合、配列の内容は配列オブジェクトの最大幅まで間隔が調整されます。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 配列要素間の垂直間隔のタイプ |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 配列要素間の垂直間隔のタイプ |
| [getRowSpacing()](#getRowSpacing--) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、単位はポイント（Exactly）または半行（Multiple）です。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、単位はポイント（Exactly）または半行（Multiple）です。 |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

配列の項目の集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**戻り値:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

配列の配置を周囲のテキストに対して指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に合わせて配置できます。デフォルト値: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**戻り値:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

配列の配置を周囲のテキストに対して指定します。配列外のテキストは、配列オブジェクトの下部、上部、または中央に合わせて配置できます。デフォルト値: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

最大分布。true の場合、配列は含む要素（ページ、列、セルなど）の最大幅まで間隔が調整されます。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**戻り値:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

最大分布。true の場合、配列は含む要素（ページ、列、セルなど）の最大幅まで間隔が調整されます。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

オブジェクト分布。true の場合、配列の内容は配列オブジェクトの最大幅まで間隔が調整されます。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**戻り値:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

オブジェクト分布。true の場合、配列の内容は配列オブジェクトの最大幅まで間隔が調整されます。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

配列要素間の垂直間隔のタイプ

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**戻り値:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

配列要素間の垂直間隔のタイプ

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、単位はポイント（Exactly）または半行（Multiple）です。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**戻り値:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用されます。その場合、単位はポイント（Exactly）または半行（Multiple）です。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |