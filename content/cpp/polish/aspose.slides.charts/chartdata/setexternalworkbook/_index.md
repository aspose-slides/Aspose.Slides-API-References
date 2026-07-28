---
title: SetExternalWorkbook()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu.
type: docs
weight: 183
url: /pl/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) metoda

Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. [Chart](../../chart/) dane zostaną zaktualizowane z docelowego skoroszytu.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Ścieżka do docelowego skoroszytu |
## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) metoda

Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Ścieżka do docelowego skoroszytu |
| updateChartData | **bool** | Jeśli wartość jest false, tylko ścieżka do skoroszytu zostanie zaktualizowana. [Chart](../../chart/) dane nie będą ładowane i aktualizowane z docelowego skoroszytu. Można użyć, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny. Jeśli wartość jest true, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |
## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ChartData](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)