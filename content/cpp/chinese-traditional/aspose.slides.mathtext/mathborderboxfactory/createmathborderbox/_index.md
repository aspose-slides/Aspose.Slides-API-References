---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API 參考
description: 透過套用於元素來建立數學邊框方塊
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) 方法

透過套用於元素來建立數學邊框方塊

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的數學元素 |

### 返回值

新的邊框方塊元素

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 方法

透過套用於元素來建立數學邊框方塊

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的數學元素 |
| hideTop | **bool** | 隱藏上邊緣 |
| hideBottom | **bool** | 隱藏下邊緣 |
| hideLeft | **bool** | 隱藏左邊緣 |
| hideRight | **bool** | 隱藏右邊緣 |
| strikethroughHorizontal | **bool** | 邊框方塊水平刪除線 |
| strikethroughVertical | **bool** | 邊框方塊垂直刪除線 |
| strikethroughBottomLeftToTopRight | **bool** | 邊框方塊左下至右上刪除線 |
| strikethroughTopLeftToBottomRight | **bool** | 邊框方塊左上至右下刪除線 |

### 返回值

新的邊框方塊元素

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBorderBox](../../imathborderbox/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBorderBoxFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)