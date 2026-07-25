---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しい二階調（黒/白）エフェクトを追加します。
type: docs
weight: 144
url: /ja/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) メソッド

コレクションの末尾に新しい二階調（黒/白）エフェクトを追加します。

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | **float** | Bi-Level エフェクトの輝度しきい値。しきい値以上の値は白に設定され、しきい値未満の値は黒に設定されます。 |

### 戻り値

コレクション内の新しい画像エフェクトのインデックスです。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBiLevel](../../ibilevel/)
* クラス [ImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)