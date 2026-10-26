---
title: AddChart()
second_title: Aspose.Slides C++ API 참조
description: 새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 모양 컬렉션의 끝에 추가합니다.
type: docs
weight: 66
url: /ko/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) 메서드

새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 모양 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 추가할 차트의 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 차트의 너비(포인트 단위)입니다. |
| height | **float** | 차트의 높이(포인트 단위)입니다. |

### 반환 값

새로 만든 [Charts::IChart](../../../aspose.slides.charts/ichart/)입니다.

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/)에서 차트를 만드는 방법을 보여줍니다. 
```cpp
// PPTX 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();
// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);
// 기본 데이터가 포함된 차트를 추가합니다
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// 차트 제목을 설정합니다
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// 첫 번째 시리즈에 값을 표시하도록 설정합니다
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// 차트 데이터 시트의 인덱스를 설정합니다
int32_t defaultWorksheetIndex = 0;
// 차트 데이터 워크시트를 가져옵니다
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// 기본으로 생성된 시리즈와 카테고리를 삭제합니다
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// 새 시리즈를 추가합니다
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// 새 카테고리를 추가합니다
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// 첫 번째 차트 시리즈를 가져옵니다
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// 시리즈 데이터를 채웁니다
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// 시리즈의 채우기 색상을 설정합니다
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// 두 번째 차트 시리즈를 가져옵니다
series = chart->get_ChartData()->get_Series()->idx_get(1);
// 시리즈 데이터를 채웁니다
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// 시리즈의 채우기 색상을 설정합니다
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// 첫 번째 레이블에 카테고리 이름을 표시하도록 설정합니다
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// 세 번째 레이블에 값을 표시하도록 시리즈를 설정합니다
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// PPTX 파일을 디스크에 저장합니다
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) 메서드

새 차트를 만들고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 모양 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 추가할 차트의 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 차트의 너비(포인트 단위)입니다. |
| height | **float** | 차트의 높이(포인트 단위)입니다. |
| initWithSample | **bool** | true인 경우 샘플 시리즈 데이터와 설정으로 차트를 초기화하고, false인 경우 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |

### 반환 값

새로 만든 [Charts::IChart](../../../aspose.slides.charts/ichart/)입니다.

## 참고

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)