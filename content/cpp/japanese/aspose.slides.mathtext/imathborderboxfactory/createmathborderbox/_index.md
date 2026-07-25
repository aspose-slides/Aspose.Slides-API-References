---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素に適用して数式ボーダーボックスを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) メソッド


要素に適用して数式ボーダーボックスを作成します

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスを適用する数式要素 |

### Return Value

新しいボーダーボックス要素

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) メソッド


要素に適用して数式ボーダーボックスを作成します

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ボーダーボックスを適用する数式要素 |
| hideTop | **bool** | 上端を非表示 |
| hideBottom | **bool** | 下端を非表示 |
| hideLeft | **bool** | 左端を非表示 |
| hideRight | **bool** | 右端を非表示 |
| strikethroughHorizontal | **bool** | 水平のボーダーボックス取り消し線 |
| strikethroughVertical | **bool** | 垂直のボーダーボックス取り消し線 |
| strikethroughBottomLeftToTopRight | **bool** | 左下から右上へのボーダーボックス取り消し線 |
| strikethroughTopLeftToBottomRight | **bool** | 左上から右下へのボーダーボックス取り消し線 |

### Return Value

新しいボーダーボックス要素

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)