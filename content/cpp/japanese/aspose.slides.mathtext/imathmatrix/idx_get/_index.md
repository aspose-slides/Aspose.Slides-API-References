---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 行列の要素
type: docs
weight: 209
url: /ja/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) メソッド

行列の要素

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | 取得するアイテムの row のゼロベースインデックス |
| column | **int32_t** | 取得するアイテムの column のゼロベースインデックス |

### 戻り値


## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)