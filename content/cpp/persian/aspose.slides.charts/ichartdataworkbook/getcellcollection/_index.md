---
title: GetCellCollection()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعهٔ سلول‌ها را دریافت می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) method


مجموعهٔ سلول‌ها را دریافت می‌کند.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) فرمولی مانند \"Sheet1!$A$2:$A$5\". |
| skipHiddenCells | **bool** | اگر true باشد، متد مجموعه‌ای بدون سلول‌های مخفی را برمی‌گرداند. |

### مقدار برگشتی

مجموعهٔ سلول‌ها [IChartCellCollection](../../ichartcellcollection/)

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCellCollection](../../ichartcellcollection/)
* کلاس [String](../../../system/string/)
* کلاس [IChartDataWorkbook](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)