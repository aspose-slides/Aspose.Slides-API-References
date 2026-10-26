---
title: SetExternalWorkbook()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Nastavuje externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu.
type: docs
weight: 196
url: /cs/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metoda

Nastavuje externí sešit jako zdroj dat pro graf. [Chart](../../chart/) data budou aktualizována z cílového sešitu.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
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

## IChartData::SetExternalWorkbook(System::String, bool) metoda

Nastavuje externí sešit jako zdroj dat pro graf.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Cesta k cílovému sešitu |
| updateChartData | **bool** | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu. [Chart](../../chart/) data nebudou načtena a aktualizována z cílového sešitu. Lze použít, když cílový sešit neexistuje nebo není dostupný. Pokud je hodnota true, budou data grafu aktualizována z cílového sešitu. |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IChartData](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)