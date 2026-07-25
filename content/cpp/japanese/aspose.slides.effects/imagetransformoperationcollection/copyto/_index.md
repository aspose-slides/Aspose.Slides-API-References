---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーし、特定の System::Array インデックスから開始します。"
type: docs
weight: 326
url: /ja/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) メソッド

[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーし、特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | [ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先である一次元 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) はゼロベースインデックスである必要があります。 |
| arrayIndex | **int32_t** | コピーが開始される *array* 内のゼロベースインデックス。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IImageTransformOperation](../../iimagetransformoperation/)
* クラス [ImageTransformOperationCollection](../)
* 名前空間 [Aspose::Slides::Effects](../../)
* ライブラリ [Aspose.Slides](../../../)