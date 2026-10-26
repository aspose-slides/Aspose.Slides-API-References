---
title: IBlur
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 塗りつぶしを含むシェイプ全体に適用されるぼかし効果を表します。
type: docs
url: /ja/com.aspose.slides/iblur/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

シェイプ全体（塗りつぶしを含む）に適用されるぼかし効果を表します。アルファを含むすべてのカラーチャンネルが影響を受けます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


ぼかし半径を取得または設定します。読み取り/書き込み可能な double。

**戻り値:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


ぼかし半径を取得または設定します。読み取り/書き込み可能な double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


オブジェクトの境界がぼかしの結果として拡大されるかどうかを決定します。true は境界が拡大されることを示し、false は拡大されないことを示します。読み取り/書き込み可能な boolean。

**戻り値:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


オブジェクトの境界がぼかしの結果として拡大されるかどうかを決定します。true は境界が拡大されることを示し、false は拡大されないことを示します。読み取り/書き込み可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |