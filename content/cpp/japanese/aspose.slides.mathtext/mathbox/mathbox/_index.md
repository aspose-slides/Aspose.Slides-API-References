---
title: MathBox()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された要素を引数として MathBox を初期化します
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) コンストラクター


[MathBox](../) を指定された要素を引数として初期化します

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボックスが適用される基底要素です。null にすることができます。 |
## 備考



例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)