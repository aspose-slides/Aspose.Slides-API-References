---
title: AddChart()
second_title: Referencia de la API Aspose.Slides para C++
description: Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo agrega al final de la colección de formas.
type: docs
weight: 66
url: /es/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a agregar. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |

### Valor devuelto

El [Charts::IChart](../../../aspose.slides.charts/ichart/) creado recientemente.

## Observaciones



El siguiente ejemplo muestra cómo crear Chart en PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancia la clase Presentation que representa un archivo PPTX
auto pres = System::MakeObject<Presentation>();
// Accede a la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Agrega un gráfico con sus datos predeterminados
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Establece el título del gráfico
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Configura la primera serie para mostrar valores
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Establece el índice para la hoja de datos del gráfico
int32_t defaultWorksheetIndex = 0;
// Obtiene la hoja de datos del gráfico
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Elimina las series y categorías generadas por defecto
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Añade nuevas series
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Añade nuevas categorías
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Obtiene la primera serie del gráfico
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Rellena los datos de la serie
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Establece el color de relleno para la serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Obtiene la segunda serie del gráfico
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Rellena los datos de la serie
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Establece el color de relleno para la serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Establece la primera etiqueta para mostrar el nombre de la categoría
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Configura la serie para mostrar el valor en la tercera etiqueta
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Guarda el archivo PPTX en disco
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a agregar. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |
| initWithSample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de series de muestra; false para crear el gráfico sin series y solo con configuraciones mínimas, lo que hace que la creación sea más rápida. |

### Valor devuelto

El [Charts::IChart](../../../aspose.slides.charts/ichart/) creado recientemente.

## Véase también

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)