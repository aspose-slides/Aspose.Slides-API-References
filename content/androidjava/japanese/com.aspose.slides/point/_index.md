---
title: Point
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: アニメーションポイントを表します。
type: docs
url: /ja/com.aspose.slides/point/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)  
```
public class Point implements IPoint
```

アニメーションポイントを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Point()](#Point--) | デフォルトコンストラクタ。 |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | 時間、値、式を使用してアニメーションポイントを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTime()](#getTime--) | 時間の値を表します。 |
| [setTime(float value)](#setTime-float-) | 時間の値を表します。 |
| [getValue()](#getValue--) | ポイントの値を表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | ポイントの値を表します。 |
| [getFormula()](#getFormula--) | 値、from、to、by 属性内の式は、次のものから構成できます: 標準の算術演算子: '+', '-', '\*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角関数演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 値、from、to、by 属性内の式は、次のものから構成できます: 標準の算術演算子: '+', '-', '\*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角関数演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String。 |

### Point() {#Point--}
```
public Point()
```

デフォルトコンストラクタ。

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

時間、値、式を使用してアニメーションポイントを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| time | float | 時間の値。 |
| value | java.lang.Object | ポイントの値。 |
| formula | java.lang.String | 式。 |

### getTime() {#getTime--}
```
public final float getTime()
```

時間の値を表します。読み書き可能な float。

**戻り値:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

時間の値を表します。読み書き可能な float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

ポイントの値を表します。のみ: bool, ColorFormat, float, int, string. 読み書き可能な Object。

**戻り値:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

ポイントの値を表します。のみ: bool, ColorFormat, float, int, string. 読み書き可能な Object。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

値、from、to、by 属性内の式は、次のものから構成できます: 標準の算術演算子: '+', '-', '\*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角関数演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String。

**戻り値:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

値、from、to、by 属性内の式は、次のものから構成できます: 標準の算術演算子: '+', '-', '\*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角関数演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |