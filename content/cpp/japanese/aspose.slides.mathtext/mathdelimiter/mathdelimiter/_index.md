---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された要素を単一の基底引数として MathDelimiter を初期化します
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) コンストラクタ


指定された要素を単一の基底引数として [MathDelimiter](../) を初期化します

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | デリミタが適用される基底要素です。null にすることができます。 |
## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)