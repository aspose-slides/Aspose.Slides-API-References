---
title: MathArray
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 方程式または任意の数学オブジェクトの垂直配列を指定します
type: docs
url: /ja/com.aspose.slides/matharray/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

配列は垂直方向の方程式または任意の数学オブジェクトの集合を指定します

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | 数学配列を作成し、指定された要素を配置します |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 数学配列を作成し、指定された要素を配置します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 配列の項目の集合 |
| [getBaseJustification()](#getBaseJustification--) | 配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | 最大分布: true の場合、配列は含む要素 (ページ、列、セル等) の最大幅に合わせて配置されます。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 最大分布: true の場合、配列は含む要素 (ページ、列、セル等) の最大幅に合わせて配置されます。 |
| [getObjectDistribution()](#getObjectDistribution--) | オブジェクト分布: true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | オブジェクト分布: true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 配列要素間の垂直間隔の種類 デフォルト: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 配列要素間の垂直間隔の種類 デフォルト: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用され、単位はポイント（Exactly）または半行（Multiple）です。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用され、単位はポイント（Exactly）または半行（Multiple）です。 |
| [getChildren()](#getChildren--) | 子要素を取得します |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


配列を作成し、指定された要素を配置します

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 配列に配置する要素 |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


配列を作成し、指定された要素を配置します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 配列に配置する要素 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


配列の項目の集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
>  ```

**戻り値:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。 デフォルト値: Center

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
public final void setBaseJustification(int value)
```


配列の配置を周囲のテキストに対して指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に揃えることができます。 デフォルト値: Center

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
public final boolean getMaximumDistribution()
```


最大分布: true の場合、配列は含む要素 (ページ、列、セル等) の最大幅に合わせて配置されます。

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
public final void setMaximumDistribution(boolean value)
```


最大分布: true の場合、配列は含む要素 (ページ、列、セル等) の最大幅に合わせて配置されます。

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
public final boolean getObjectDistribution()
```


オブジェクト分布: true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。

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
public final void setObjectDistribution(boolean value)
```


オブジェクト分布: true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。

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
public final int getRowSpacingRule()
```


配列要素間の垂直間隔の種類 デフォルト: SingleLineGap

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
public final void setRowSpacingRule(int value)
```


配列要素間の垂直間隔の種類 デフォルト: SingleLineGap

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
public final long getRowSpacing()
```


配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用され、単位はポイント（Exactly）または半行（Multiple）です。 デフォルト: 0

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
public final void setRowSpacing(long value)
```


配列の行間の間隔。RowSpacingRule が 3 に設定されている場合にのみ使用され、単位はポイント（Exactly）または半行（Multiple）です。 デフォルト: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]