---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから特定のオブジェクトの最初の出現を削除します。
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) メソッド

コレクションから特定のオブジェクトの最初の出現を削除します。

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | コレクションから削除するオブジェクト。 |

### 戻り値

コレクションから*item* が正常に削除された場合は true、そうでない場合は false を返します。このメソッドは、元のコレクションに*item* が見つからない場合も false を返します。

## 備考



例: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)