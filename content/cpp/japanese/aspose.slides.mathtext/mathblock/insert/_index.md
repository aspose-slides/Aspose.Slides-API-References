---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに MathElement をコレクションに挿入します。
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) メソッド


指定されたインデックスに MathElement をコレクションへ挿入します。

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | MathElement を挿入するゼロベースのインデックスです。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 挿入する MathElement。 |
## 備考



例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)