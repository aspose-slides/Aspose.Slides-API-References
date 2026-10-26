---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Bi-Level（白黒）エフェクトをコレクションの末尾に追加します。
type: docs
weight: 118
url: /ja/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) メソッド

新しい Bi-Level（白黒）エフェクトをコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | **float** | Bi-Level エフェクトの輝度しきい値。しきい値以上の値は白に設定されます。しきい値未満の値は黒に設定されます。 |

### 戻り値

コレクション内の新しい画像エフェクトのインデックス。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBiLevel](../../ibilevel/)
* クラス [IImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)