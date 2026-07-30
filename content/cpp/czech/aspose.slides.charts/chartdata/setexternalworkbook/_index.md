---
title: SetExternalWorkbook()
second_title: Aspose.Slides pro C++ Referenční příručka API
description: Nastaví externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu.
type: docs
weight: 183
url: /cs/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) metoda

Nastaví externí sešit jako zdroj dat pro graf. [Chart](../../chart/) data budou aktualizována z cílového sešitu.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Cesta k cílovému sešitu |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) metoda

Nastaví externí sešit jako zdroj dat pro graf.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Cesta k cílovému sešitu |
| updateChartData | **bool** | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu. [Chart](../../chart/) data nebudou načtena a aktualizována z cílového sešitu. Lze použít, když cílový sešit neexistuje nebo není dostupný. Pokud je hodnota true, data grafu budou aktualizována z cílového sešitu. |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)