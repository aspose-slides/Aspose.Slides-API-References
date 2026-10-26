---
title: CreateMathBorderBox()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 要素に適用して数式ボーダーボックスを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


要素に適用して数学ボーダーボックスを作成します

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスを適用する数学要素 |

### 戻り値

新しいボーダーボックス要素

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


要素に適用して数学ボーダーボックスを作成します

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスを適用する数学要素 |
| hideTop | **bool** | 上端を非表示 |
| hideBottom | **bool** | 下端を非表示 |
| hideLeft | **bool** | 左端を非表示 |
| hideRight | **bool** | 右端を非表示 |
| strikethroughHorizontal | **bool** | ボーダーボックスの水平取り消し線 |
| strikethroughVertical | **bool** | ボーダーボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | **bool** | ボーダーボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | **bool** | ボーダーボックスの左上から右下への取り消し線 |

### 戻り値

新しいボーダーボックス要素

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)