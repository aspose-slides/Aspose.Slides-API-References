---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API リファレンス
description: 長方形の枠線を持つ MathBorderBox 要素を作成します
type: docs
weight: 222
url: /ja/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) コンストラクタ

[MathBorderBox](../) 要素を長方形の枠で作成します

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスが適用されるベース要素です。null にすることができます。 |
## 備考



例: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) コンストラクタ

[MathBorderBox](../) 要素を作成します

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスが適用されるベース要素 |
| hideTop | **bool** | 上端を非表示にします |
| hideBottom | **bool** | 下端を非表示にします |
| hideLeft | **bool** | 左端を非表示にします |
| hideRight | **bool** | 右端を非表示にします |
| strikethroughHorizontal | **bool** | 水平に取り消し線を引く |
| strikethroughVertical | **bool** | 垂直に取り消し線を引く |
| strikethroughBottomLeftToTopRight | **bool** | 左下から右上へ取り消し線を引く |
| strikethroughTopLeftToBottomRight | **bool** | 左上から右下へ取り消し線を引く |
## 備考



例: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)