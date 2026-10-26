---
title: idx_set()
second_title: Aspose.Slides for C++ API リファレンス
description: 行列の要素
type: docs
weight: 222
url: /ja/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) メソッド

行列の要素

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| row | **int32_t** | アイテムを取得する行のゼロベースインデックス |
| column | **int32_t** | アイテムを取得する列のゼロベースインデックス |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)