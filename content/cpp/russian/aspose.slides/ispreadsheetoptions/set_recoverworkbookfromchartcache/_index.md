---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides для C++: справочник API
description: Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кэша диаграммы.
type: docs
weight: 40
url: /ru/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) метод


Если источник данных для диаграммы является внешней книгой и он недоступен, он будет восстановлен из кэша диаграммы.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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