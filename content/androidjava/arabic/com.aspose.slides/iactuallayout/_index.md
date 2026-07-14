---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /ar/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

يحدد الموقع الفعلي لعنصر المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getActualX()](#getActualX--) | يحدد الموضع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة للزاوية العليا اليسرى للمخطط. |
| [getActualY()](#getActualY--) | يحدد أعلى العنصر الفعلي للمخطط بالنسبة للزاوية العليا اليسرى للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

يحدد الموضع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة للزاوية العليا اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل ذلك للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

يحدد أعلى العنصر الفعلي للمخطط بالنسبة للزاوية العليا اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل ذلك للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل ذلك للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل ذلك للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float