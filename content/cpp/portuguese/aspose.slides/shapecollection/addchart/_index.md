---
title: AddChart()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.
type: docs
weight: 66
url: /pt/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) método


Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |

### Valor de Retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## Observações



O exemplo a seguir mostra como criar Chart no PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancia a classe Presentation que representa um arquivo PPTX
auto pres = System::MakeObject<Presentation>();
// Acessa o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);
// Adiciona um gráfico com seus dados padrão
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Define o título do gráfico
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Define a primeira série para mostrar valores
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Define o índice para a planilha de dados do gráfico
int32_t defaultWorksheetIndex = 0;
// Obtém a planilha de dados do gráfico
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Exclui as séries e categorias geradas por padrão
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Adiciona novas séries
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Adiciona novas categorias
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Obtém a primeira série do gráfico
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Preenche os dados da série
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Define a cor de preenchimento da série
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Obtém a segunda série do gráfico
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Preenche os dados da série
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Define a cor de preenchimento da série
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Define o primeiro rótulo para mostrar o nome da Categoria
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Define a série para mostrar o valor do terceiro rótulo
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Salva o arquivo PPTX no disco
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) método


Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | O tipo de gráfico a ser adicionado. |
| x | **float** | A coordenada x do novo gráfico, em pontos. |
| y | **float** | A coordenada y do novo gráfico, em pontos. |
| width | **float** | A largura do gráfico, em pontos. |
| height | **float** | A altura do gráfico, em pontos. |
| initWithSample | **bool** | Verdadeiro para inicializar o novo gráfico com dados de série de exemplo e configurações; falso para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

### Valor de Retorno

O [Charts::IChart](../../../aspose.slides.charts/ichart/) recém-criado.

## Ver Também

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)