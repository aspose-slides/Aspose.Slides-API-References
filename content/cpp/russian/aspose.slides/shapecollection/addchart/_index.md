---
title: AddChart()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую диаграмму, инициализирует её образцовыми данными серии и параметрами, и добавляет её в конец коллекции фигур.
type: docs
weight: 66
url: /ru/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными серии и параметрами и добавляет в конец коллекции фигур.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы, которую следует добавить. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина диаграммы в пунктах. |
| height | **float** | Высота диаграммы в пунктах. |

### Возвращаемое значение

Новосозданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Примечания

Следующий пример показывает, как создать Chart в PowerPoint [Presentation](../../presentation/). 
```cpp
// Создаёт экземпляр класса Presentation, представляющего файл PPTX
auto pres = System::MakeObject<Presentation>();
// Получает первый слайд
auto slide = pres->get_Slides()->idx_get(0);
// Добавляет диаграмму с её данными по умолчанию
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Устанавливает заголовок диаграммы
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Настраивает первую серию отображать значения
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Устанавливает индекс листа данных диаграммы
int32_t defaultWorksheetIndex = 0;
// Получает рабочий лист данных диаграммы
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Удаляет автоматически сгенерированные серии и категории
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Добавляет новую серию
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Добавляет новые категории
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Получает первую серию диаграммы
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Заполняет данные серии
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Устанавливает цвет заливки для серии
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Получает вторую серию диаграммы
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Заполняет данные серии
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Устанавливает цвет заливки для серии
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Настраивает первую подпись отображать имя категории
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Настраивает серию отображать значение для третьей подписи
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Сохраняет файл PPTX на диск
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) метод

Создаёт новую диаграмму, инициализирует её образцовыми данными серии и параметрами и добавляет в конец коллекции фигур.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Тип диаграммы, которую следует добавить. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина диаграммы в пунктах. |
| height | **float** | Высота диаграммы в пунктах. |
| initWithSample | **bool** | True — инициализировать новую диаграмму образцовыми данными серии и параметрами; false — создать диаграмму без серий и только с минимальными параметрами, что ускоряет создание. |

### Возвращаемое значение

Новосозданный [Charts::IChart](../../../aspose.slides.charts/ichart/).

## См. также

* Перечисление [ChartType](../../../aspose.slides.charts/charttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IChart](../../../aspose.slides.charts/ichart/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)