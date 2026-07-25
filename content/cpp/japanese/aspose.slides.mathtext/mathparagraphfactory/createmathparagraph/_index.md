---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の数式段落を作成
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathparagraphfactory/createmathparagraph/
---
## MathParagraphFactory::CreateMathParagraph() method

空の数式段落を作成

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph() override
```

### 戻り値

新しい数式段落

## MathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) method

数式段落を作成し、指定された数式ブロックを配置します

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 段落に配置する数式ブロック |

### 戻り値

新しい数式段落

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathParagraph](../../imathparagraph/)
* クラス [MathParagraphFactory](../)
* クラス [IMathBlock](../../imathblock/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)