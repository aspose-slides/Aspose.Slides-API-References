---
title: SetExternalWorkbook()
second_title: Referência da API Aspose.Slides para C++
description: Define uma pasta de trabalho externa como fonte de dados para o gráfico. Os dados do gráfico serão atualizados a partir da pasta de trabalho de destino.
type: docs
weight: 196
url: /pt/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) método

Define uma pasta de trabalho externa como fonte de dados para o gráfico. [Chart](../../chart/) dados serão atualizados a partir da pasta de trabalho de destino.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Caminho para a pasta de trabalho de destino |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) método

Define uma pasta de trabalho externa como fonte de dados para o gráfico.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Caminho para a pasta de trabalho de destino |
| updateChartData | **bool** | Se o valor for falso, somente o caminho da pasta de trabalho será atualizado. [Chart](../../chart/) dados não serão carregados e atualizados a partir da pasta de trabalho de destino. Pode ser usado quando a pasta de trabalho de destino não existe ou não está disponível. Se o valor for verdadeiro, os dados do gráfico serão atualizados a partir da pasta de trabalho de destino. |
## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Veja também

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)