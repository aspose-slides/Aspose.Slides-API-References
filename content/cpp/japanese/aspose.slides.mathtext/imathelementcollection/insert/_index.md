---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスにコレクション内に数式要素を挿入します。
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) メソッド

指定されたインデックスにコレクション内に数式要素を挿入します。

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | [IMathElement](../../imathelement/) を挿入すべきゼロベースのインデックス。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 挿入する [IMathElement](../../imathelement/)。 |
## 備考



例:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathElementCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)