---
title: idx_set()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに IMathElement を設定します。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) メソッド

指定されたインデックスに [IMathElement](../../imathelement/) を設定します。

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | アイテムのゼロベースインデックス。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 数式要素。 |
## 備考



例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)