---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
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
| [getFormula()](#getFormula--) | values、from、to、by 属性内の数式は次のものから構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照（ホストがサポートするプロパティ）例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | values、from、to、by 属性内の数式は次のものから構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照（ホストがサポートするプロパティ）例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```


時間値を表します。読み書き可能な float。

**戻り値:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```


時間値を表します。読み書き可能な float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


ポイント値を表します。対象は: bool, ColorFormat, float, int, string のみ。読み書き可能な Object。

**戻り値:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


ポイント値を表します。対象は: bool, ColorFormat, float, int, string のみ。読み書き可能な Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


values、from、to、by 属性内の数式は次のものから構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照（ホストがサポートするプロパティ）例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String.

**戻り値:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


values、from、to、by 属性内の数式は次のものから構成できます: 標準算術演算子: '+', '-', '*', '/', '^', '%' (mod) 定数: 'pi' 'e' 条件演算子: 'abs', 'min', 'max', '?' (if) 比較演算子: '==', '>=', '', '!=', '!' 三角演算子: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然対数 'ln()' プロパティ参照（ホストがサポートするプロパティ）例: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 読み書き可能な String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |