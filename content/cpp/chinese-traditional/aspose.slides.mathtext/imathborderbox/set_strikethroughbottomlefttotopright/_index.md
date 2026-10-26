---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API 參考文件
description: 從左下角到右上角的刪除線（預設為 false）。指定邊框盒左下角到右上角的斜向刪除線的隱藏或顯示狀態。
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) 方法


從左下角到右上角的刪除線 (預設為 false)。指定邊框盒左下角到右上角的斜向刪除線的隱藏或顯示狀態。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
```

## 備註


範例： 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 另請參閱

* 類別 [IMathBorderBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)