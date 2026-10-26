---
title: IActualLayout
second_title: Aspose.Slides for Java مرجع API
description: يحدد الموضع الفعلي لعنصر المخطط.
type: docs
url: /ar/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

يحدد الموضع الفعلي لعنصر المخطط.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getActualX()](#getActualX--) | يحدد الموضع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualY()](#getActualY--) | يحدد أعلى العنصر الفعلي للمخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

يحدد الموضع الفعلي للمحور x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

يحدد أعلى العنصر الفعلي للمخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() أولاً للحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float