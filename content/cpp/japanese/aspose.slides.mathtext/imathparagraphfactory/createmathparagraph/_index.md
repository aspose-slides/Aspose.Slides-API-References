---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の数式段落を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() メソッド

空の数式段落を作成する

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```

### 戻り値

新しい数式段落

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) メソッド

数式段落を作成し、指定された数式ブロックをその中に配置します

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 段落に配置する数式ブロック |

### 戻り値

新しい数式段落

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathParagraph](../../imathparagraph/)
* Class [IMathParagraphFactory](../)
* Class [IMathBlock](../../imathblock/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)