---
title: IMathArray
second_title: Aspose.Slides for Java API リファレンス
description: 数式または任意の数学的オブジェクトの垂直配列を指定します
type: docs
url: /ja/com.aspose.slides/imatharray/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

数式または任意の数学的オブジェクトの垂直配列を指定します

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 配列の項目のセット |
| [getBaseJustification()](#getBaseJustification--) | 配列の周囲のテキストに対する配置を指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に配置できます。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 配列の周囲のテキストに対する配置を指定します。配列の外側のテキストは、配列オブジェクトの下部、上部、または中央に配置できます。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。 |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 配列要素間の垂直間隔のタイプ |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 配列要素間の垂直間隔のタイプ |
| [getRowSpacing()](#getRowSpacing--) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合のみ使用されます。その場合、単位はポイント（Exactly）またはハーフライン（Multiple）です。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 配列の行間の間隔。RowSpacingRule が 3 に設定されている場合のみ使用されます。その場合、単位はポイント（Exactly）またはハーフライン（Multiple）です。 |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

配列の項目のセット

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

配列の周囲のテキストに対する配置を指定します。配列の外側のテキストは配列オブジェクトの下部、上部、または中央に配置できます。デフォルト値: Center

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

配列の周囲のテキストに対する配置を指定します。配列の外側のテキストは配列オブジェクトの下部、上部、または中央に配置できます。デフォルト値: Center

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

Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。

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

Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。

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

Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。

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

Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます。

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

配列の行間の間隔。RowSpacingRule が 3 に設定されている場合のみ使用されます。その場合、単位はポイント（Exactly）またはハーフライン（Multiple）です。デフォルト: 0

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

配列の行間の間隔。RowSpacingRule が 3 に設定されている場合のみ使用されます。その場合、単位はポイント（Exactly）またはハーフライン（Multiple）です。デフォルト: 0

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