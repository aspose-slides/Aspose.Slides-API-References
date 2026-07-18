---
title: AddChart()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματικά δεδομένα σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 66
url: /el/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) μέθοδος


Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δεδομένα και ρυθμίσεις δείγματικών σειρών, και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του γραφήματος προς προσθήκη. |
| x | **float** | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | **float** | Το πλάτος του γραφήματος, σε σημεία. |
| height | **float** | Το ύψος του γραφήματος, σε σημεία. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Σχόλια



Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε ένα Chart στο PowerPoint [Presentation](../../presentation/). 
```cpp
// Δημιουργεί ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει ένα αρχείο PPTX
auto pres = System::MakeObject<Presentation>();
// Προσεγγίζει την πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);
// Προσθέτει ένα γράφημα με τα προεπιλεγμένα δεδομένα του
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Ορίζει τον τίτλο του γραφήματος
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Ορίζει την πρώτη σειρά να δείχνει τιμές
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Ορίζει το δείκτη για το φύλλο δεδομένων του γραφήματος
int32_t defaultWorksheetIndex = 0;
// Λαμβάνει το φύλλο δεδομένων του γραφήματος
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Διαγράφει τις προεπιλεγμένες δημιουργημένες σειρές και κατηγορίες
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Προσθέτει νέες σειρές
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Προσθέτει νέες κατηγορίες
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Παίρνει την πρώτη σειρά του γραφήματος
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Γεμίζει τα δεδομένα της σειράς
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Ορίζει το χρώμα γεμίσματος για τη σειρά
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Παίρνει τη δεύτερη σειρά του γραφήματος
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Γεμίζει τα δεδομένα της σειράς
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Ορίζει το χρώμα γεμίσματος για τη σειρά
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Ορίζει την πρώτη ετικέτα να εμφανίζει το όνομα της κατηγορίας
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Ορίζει τη σειρά να εμφανίζει την τιμή για την τρίτη ετικέτα
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Αποθηκεύει το αρχείο PPTX στο δίσκο
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) μέθοδος


Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δεδομένα και ρυθμίσεις δείγματικών σειρών, και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Ο τύπος του γραφήματος προς προσθήκη. |
| x | **float** | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | **float** | Το πλάτος του γραφήματος, σε σημεία. |
| height | **float** | Το ύψος του γραφήματος, σε σημεία. |
| initWithSample | **bool** | True για να αρχικοποιηθεί το νέο γράφημα με δείγματικά δεδομένα σειράς και ρυθμίσεις· false για δημιουργία γραφήματος χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, κάτι που κάνει τη δημιουργία γρηγορότερη. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Δείτε επίσης

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)