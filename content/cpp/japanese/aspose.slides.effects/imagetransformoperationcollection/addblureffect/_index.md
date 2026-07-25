---
title: AddBlurEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Blur エフェクトをコレクションの末尾に追加します。
type: docs
weight: 157
url: /ja/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) メソッド

新しい[Blur](../../blur/)エフェクトをコレクションの末尾に追加します。

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| radius | **double** | ぼかしの半径。 |
| grow | **bool** | ブラー処理の結果としてオブジェクトの境界を拡張するかどうかを指定します。true は境界が拡張されることを示し、false は拡張されないことを示します。 |

### 戻り値

コレクション内の新しい画像エフェクトのインデックス。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBlur](../../iblur/)
* クラス [ImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)