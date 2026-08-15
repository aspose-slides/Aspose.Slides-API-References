---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API 參考
description: "最小欄寬（以 twips 為單位，1 點的 1/20），間距（亦稱 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）會加至 MinColumnWidth，以確定總 Matrix 欄位間距（不同欄位相同邊緣之間的距離）。預設值：0。"
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) 方法

最小欄寬（以 twips 為單位，1 點的 1/20）間距（亦稱「Column Gap」或「Gap Width」）會加至 MinColumnWidth，以確定總 Matrix [Column](../../../aspose.slides/column/) Spacing（不同欄位相同邊緣之間的距離）。預設值：0。

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另請參閱

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)