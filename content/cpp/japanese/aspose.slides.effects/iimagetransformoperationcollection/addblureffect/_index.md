---
title: AddBlurEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しい Blur エフェクトを追加します。
type: docs
weight: 131
url: /ja/aspose.slides.effects/iimagetransformoperationcollection/addblureffect/
---
## IImageTransformOperationCollection::AddBlurEffect(double, bool) メソッド

コレクションの末尾に新しい[Blur](../../blur/)エフェクトを追加します。

```cpp
virtual System::SharedPtr<IBlur> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBlurEffect(double radius, bool grow)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| radius | **double** | ブラーの半径。 |
| grow | **bool** | ブラー処理の結果としてオブジェクトの境界を拡張すべきかどうかを指定します。True は境界が拡張されることを示し、false は拡張されないことを示します。 |

### 戻り値

コレクション内の新しい画像エフェクトのインデックス。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBlur](../../iblur/)
* クラス [IImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)