---
title: IAlphaBiLevel
second_title: Aspose.Slides for Android via Java API リファレンス
description: Alpha Bi-Level エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/ialphabilevel/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha (不透明度) の値は 0 (完全に透明) に、しきい値以上の Alpha の値は 100% (完全に不透明) に変換されます。

--------------------

COM でインスタンスを作成するには ImageTransformOperationFactory を使用します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | エフェクトのしきい値を返します。 |
| [setThreshold(float value)](#setThreshold-float-) | エフェクトのしきい値を返します。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

エフェクトのしきい値を返します。読み取り/書き込み float.

**戻り値:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

エフェクトのしきい値を返します。読み取り/書き込み float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |