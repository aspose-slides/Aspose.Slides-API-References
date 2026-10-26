---
title: get_RecoverWorkbookFromChartCache()
second_title: Справочник API Aspose.Slides для C++
description: Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграммы.
type: docs
weight: 27
url: /ru/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() метод


Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграммы.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```

## Примечания



Пример:
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## См. также

* Класс [ISpreadsheetOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)