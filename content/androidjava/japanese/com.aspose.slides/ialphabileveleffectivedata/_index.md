---
title: IAlphaBiLevelEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Alpha Bi-Level エフェクトを表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ialphabileveleffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Alpha Bi-Level エフェクトを表す不変オブジェクトです。しきい値未満の Alpha (Opacity) の値は 0 (完全に透明) に、しきい値以上の Alpha の値は 100% (完全に不透明) に変更されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 効果のしきい値を返します。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

効果のしきい値を返します。読み取り専用 float.

**戻り値:**
float