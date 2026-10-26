---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーします。コピーは特定の System::Array インデックスから開始します。"
type: docs
weight: 118
url: /ja/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) メソッド

[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーします。コピーは特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | [System::Array](../../../system/array/) の一次元配列で、[ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先です。[System::Array](../../../system/array/) はゼロベースのインデックスを持つ必要があります。 |
| arrayIndex | **int32_t** | コピー開始位置となる *array* のゼロベースインデックスです。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)