---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از گروه‌های سری‌های ترکیبی.
type: docs
url: /fa/com.aspose.slides/ichartseriesgroupcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

نمایانگر مجموعه‌ای از گروه‌های سری‌های ترکیبی است.

--------------------

1) هر گروه از سری‌ها شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروه از سری‌ها شامل سری‌ای است که بر روی محورهای اصلی یا محورهای ثانویه (نه هر دو در یک گروه) رسم می‌شود. بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس گروه‌های نوع مذکور و نوع رسم اصلی/ثانویه است. 2) گروه سری‌ها شامل برخی از ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). "Series group properties" در کلاس ChartSeriesGroup قابلیت خواندن/نوشتن دارد. هر یک از "series group properties" می‌تواند یک پروژکشن فقط-خواندنی در کلاس ChartSeries داشته باشد.

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

**بازگرداندن:**
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

**بازگرداندن:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)