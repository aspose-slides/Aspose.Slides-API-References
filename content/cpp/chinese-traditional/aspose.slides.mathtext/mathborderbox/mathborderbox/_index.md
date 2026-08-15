---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有矩形邊框的 MathBorderBox 元素
type: docs
weight: 222
url: /zh-hant/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) 建構函式


建立 [MathBorderBox](../) 元素，具有矩形邊框

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的基礎元素。可以為 null。 |
## 備註



範例： 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 建構函式


建立 [MathBorderBox](../) 元素

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用邊框方塊的基礎元素 |
| hideTop | **bool** | 隱藏上緣 |
| hideBottom | **bool** | 隱藏下緣 |
| hideLeft | **bool** | 隱藏左緣 |
| hideRight | **bool** | 隱藏右緣 |
| strikethroughHorizontal | **bool** | 水平刪除線 |
| strikethroughVertical | **bool** | 垂直刪除線 |
| strikethroughBottomLeftToTopRight | **bool** | 從左下至右上刪除線 |
| strikethroughTopLeftToBottomRight | **bool** | 從左上至右下刪除線 |
## 備註



範例： 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)