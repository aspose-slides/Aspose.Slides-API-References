---
title: AxisAggregationType
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده نوع تجمیع محور دسته‌بندی.
type: docs
url: /fa/com.aspose.slides/axisaggregationtype/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AxisAggregationType extends System.Enum
```

نوع ترکیب محور دسته‌بندی را نشان می‌دهد. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [ByCategory](#ByCategory) | Aggregate by categories |
| [Automatic](#Automatic) | Aggregate categories automatically. |
| [ByBinWidth](#ByBinWidth) | Aggregate categories by bin width. |
| [ByNumberOfBins](#ByNumberOfBins) | Aggregate categories by number of bins. |
### ByCategory {#ByCategory}
```
public static final int ByCategory
```

تجمع بر اساس دسته‌ها

### Automatic {#Automatic}
```
public static final int Automatic
```

دسته‌ها را به‌صورت خودکار تجمع می‌کند.

### ByBinWidth {#ByBinWidth}
```
public static final int ByBinWidth
```

دسته‌ها را بر اساس عرض بِن تجمع می‌کند. ویژگی IAxis.BinWidth باید تنظیم شود.

### ByNumberOfBins {#ByNumberOfBins}
```
public static final int ByNumberOfBins
```

دسته‌ها را بر اساس تعداد بِن‌ها تجمع می‌کند. ویژگی IAxis.NumberOfBins باید تنظیم شود.