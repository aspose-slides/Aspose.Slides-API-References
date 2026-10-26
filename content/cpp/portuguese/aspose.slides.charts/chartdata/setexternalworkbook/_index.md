---
title: SetExternalWorkbook()
second_title: Referência da API Aspose.Slides para C++
description: Define a planilha externa como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir da planilha de destino.
type: docs
weight: 183
url: /pt/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) método

Define a planilha externa como fonte de dados para o gráfico. [Chart](../../chart/) os dados serão atualizados a partir da planilha de destino.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Caminho para a planilha de destino |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) método

Define a planilha externa como fonte de dados para o gráfico.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Caminho para a planilha de destino |
| updateChartData | **bool** | Se o valor for false, apenas o caminho da planilha será atualizado. [Chart](../../chart/) os dados não serão carregados e atualizados a partir da planilha de destino. Pode ser usado quando a planilha de destino não existe ou não está disponível. Se o valor for true, os dados do gráfico serão atualizados a partir da planilha de destino. |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Ver Também

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)