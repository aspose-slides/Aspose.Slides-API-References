---
title: IPropertyEffect
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: プロパティ効果の動作を表します。
type: docs
url: /ja/com.aspose.slides/ipropertyeffect/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

プロパティ効果の動作を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrom()](#getFrom--) | アニメーションの開始値を指定します。 |
| [setFrom(String value)](#setFrom-java.lang.String-) | アニメーションの開始値を指定します。 |
| [getTo()](#getTo--) | アニメーションの終了値を指定します。 |
| [setTo(String value)](#setTo-java.lang.String-) | アニメーションの終了値を指定します。 |
| [getBy()](#getBy--) | アニメーション開始前の位置に対する相対オフセット値を指定します。 |
| [setBy(String value)](#setBy-java.lang.String-) | アニメーション開始前の位置に対する相対オフセット値を指定します。 |
| [getValueType()](#getValueType--) | プロパティ値の型を指定します。 |
| [setValueType(int value)](#setValueType-int-) | プロパティ値の型を指定します。 |
| [getCalcMode()](#getCalcMode--) | アニメーションの補間モードを指定します（読み取り/書き込み） [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [setCalcMode(int value)](#setCalcMode-int-) | アニメーションの補間モードを指定します（読み取り/書き込み） [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [getPoints()](#getPoints--) | アニメーションのポイントを指定します。 |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | アニメーションのポイントを指定します。 |

### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

アニメーションの開始値を指定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

アニメーションの開始値を指定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

アニメーションの終了値を指定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

アニメーションの終了値を指定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

アニメーション開始前の位置に対する相対オフセット値を指定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

アニメーション開始前の位置に対する相対オフセット値を指定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

プロパティ値の型を指定します。読み取り/書き込み [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**戻り値:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

プロパティ値の型を指定します。読み取り/書き込み [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

アニメーションの補間モードを指定します。読み取り/書き込み [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**戻り値:**
int

### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

アニメーションの補間モードを指定します。読み取り/書き込み [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

アニメーションのポイントを指定します。読み取り/書き込み [IPointCollection](../../com.aspose.slides/ipointcollection)。

**戻り値:**
[IPointCollection](../../com.aspose.slides/ipointcollection)

### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

アニメーションのポイントを指定します。読み取り/書き込み [IPointCollection](../../com.aspose.slides/ipointcollection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |