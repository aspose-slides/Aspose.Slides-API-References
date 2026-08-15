---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API 參考
description: 透過套用於元素來建立數學邊框方塊
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) 方法

透過套用於元素來建立數學邊框方塊

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的數學元素 |

### 回傳值

新的邊框方塊元素

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 方法

透過套用於元素來建立數學邊框方塊

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的數學元素 |
| hideTop | **bool** | 隱藏上邊緣 |
| hideBottom | **bool** | 隱藏下邊緣 |
| hideLeft | **bool** | 隱藏左邊緣 |
| hideRight | **bool** | 隱藏右邊緣 |
| strikethroughHorizontal | **bool** | 邊框方塊水平刪除線 |
| strikethroughVertical | **bool** | 邊框方塊垂直刪除線 |
| strikethroughBottomLeftToTopRight | **bool** | 邊框方塊從左下到右上刪除線 |
| strikethroughTopLeftToBottomRight | **bool** | 邊框方塊從左上到右下刪除線 |

### 回傳值

新的邊框方塊元素

## 參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBorderBox](../../imathborderbox/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathBorderBoxFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)