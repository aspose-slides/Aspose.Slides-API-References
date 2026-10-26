---
title: RemoveAt()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内の指定されたインデックスにある要素を削除します。
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) method

コレクション内の指定されたインデックスにある要素を削除します。

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 削除する要素のゼロベースインデックスです。 |
## 備考

例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## 参照

* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)