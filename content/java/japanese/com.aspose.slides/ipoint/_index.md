---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: アニメーションポイントを表します。
type: docs
url: /ja/com.aspose.slides/ipoint/
---```
public interface IPoint
```

アニメーションポイントを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTime()](#getTime--) | 時間値を表します。 |
| [setTime(float value)](#setTime-float-) | 時間値を表します。 |
| [getValue()](#getValue--) | ポイント値を表します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | ポイント値を表します。 |
| [getFormula()](#getFormula--) | 値、from、to、by 属性内の数式は以下で構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み取り/書き込み String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | 値、from、to、by 属性内の数式は以下で構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み取り/書き込み String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

時間値を表します。読み取り/書き込み float.

**戻り値:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

時間値を表します。読み取り/書き込み float.

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

ポイント値を表します。対象: bool, ColorFormat, float, int, string のみ。読み取り/書き込み Object.

**戻り値:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

ポイント値を表します。対象: bool, ColorFormat, float, int, string のみ。読み取り/書き込み Object.

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

値、from、to、by 属性内の数式は以下で構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み取り/書き込み String.

**戻り値:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

値、from、to、by 属性内の数式は以下で構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照 (ホストがサポートするプロパティ) 例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み取り/書き込み String.

**パラメーター:**
| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |