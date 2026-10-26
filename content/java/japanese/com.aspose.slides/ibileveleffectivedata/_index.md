---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 二値（黒/白）効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ibileveleffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

二値（黒/白）効果を表す不変オブジェクトです。指定された閾値未満の輝度を持つ入力色は黒に変更され、指定された閾値以上の輝度を持つ入力色は白に設定されます。アルファ効果の値はこの効果の影響を受けません。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 閾値を返します。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


閾値を返します。読み取り専用 float.

**戻り値:**
float