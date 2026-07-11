---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию листов рабочей книги данных диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartdataworksheetcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Представляет коллекцию листов рабочей книги данных диаграммы.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает лист рабочей книги по индексу. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Возвращает лист рабочей книги по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс листа в коллекции. |

**Возвращаемое значение:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Экземпляр IChartDataWorksheet.