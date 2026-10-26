---
title: MathPhantom()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたベース数式要素を使用して、MathPhantom クラスの新しいインスタンスを初期化します。
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) コンストラクタ

指定されたベースの数式要素を使用して、[MathPhantom](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Phantom によって可視性とレイアウトが制御されるベース [IMathElement](../../imathelement/)。この要素は、隠されたり表示されたりする可能性のあるコンテンツを定義し、周囲の数式の幾何学的配置にも影響を与えます。 |

## 備考

Phantom 要素は、必ずしも表示せずにベースの式の視覚的スペースを確保または抑制するために使用されます。これは OMML 要素 **<m:phant>** に対応します。

例：
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## 相关項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathPhantom](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)