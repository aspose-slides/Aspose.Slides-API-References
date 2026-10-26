---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides для C++ справочник API
description: Если источник данных для диаграммы является внешней рабочей книгой и недоступен, он будет восстановлен из кеша диаграммы.
type: docs
weight: 27
url: /ru/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() метод


Если источник данных для диаграммы является внешней рабочей книгой и недоступен, он будет восстановлен из кеша диаграммы.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

* Класс [SpreadsheetOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)