---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides C++ API 레퍼런스
description: 차트의 데이터 원본이 외부 워크북이며 사용할 수 없는 경우, 차트 캐시에서 복구됩니다.
type: docs
weight: 27
url: /ko/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() 메서드


차트의 데이터 원본이 외부 워크북이고 사용할 수 없는 경우, 차트 캐시에서 복구됩니다.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## 비고



예시: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## 참조

* 클래스 [SpreadsheetOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)