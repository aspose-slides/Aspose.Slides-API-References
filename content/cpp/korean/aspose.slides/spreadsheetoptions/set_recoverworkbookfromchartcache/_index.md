---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트의 데이터 소스가 외부 워크북이며 사용 불가능한 경우, 차트 캐시에서 복구됩니다.
type: docs
weight: 40
url: /ko/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) 메서드


차트의 데이터 소스가 외부 워크북이고 사용할 수 없는 경우, 차트 캐시에서 복구됩니다.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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

## 참고

* 클래스 [SpreadsheetOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)