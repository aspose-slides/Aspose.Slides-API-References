---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش دهنده مجموعه‌ای از گروه‌های سری‌های ترکیبی.
type: docs
url: /fa/com.aspose.slides/ichartseriesgroupcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

نمایش دهنده مجموعه‌ای از گروه‌های سری‌های ترکیبی.

--------------------

1) هر گروهی از سری‌ها شامل سری‌هایی با نوع‌های ترکیبی است. گروه‌های نوع‌های سری‌های ترکیبی با enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروهی از سری‌ها شامل سری‌هایی است که بر روی محورهای اصلی یا محورهای ثانویه (نه هر دو در یک گروه) رسم می‌شود. بنابراین اصل گروه‌بندی سری‌ها، گروه‌بندی بر مبنای گروه‌های نوع ذکر شده و نوع رسم اصلی/ثانویه است. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابلیت خواندن/نوشتن دارد. هر یک از «ویژگی‌های گروه سری» می‌تواند یک پیش‌نمایش فقط-خواندنی در کلاس ChartSeries داشته باشد.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | گروه سری را بر اساس سری دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | گروه سری را بر اساس شاخص دریافت می‌کند. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

گروه سری را بر اساس سری دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**بازگشت:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

گروه سری را بر اساس شاخص دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)