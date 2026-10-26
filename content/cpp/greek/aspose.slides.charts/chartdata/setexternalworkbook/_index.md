---
title: SetExternalWorkbook()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού.
type: docs
weight: 183
url: /el/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) μέθοδος

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. [Chart](../../chart/) τα δεδομένα θα ενημερωθούν από το βιβλίο εργασίας προορισμού.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Παράμετροι

| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Διαδρομή προς το βιβλίο εργασίας προορισμού |
## Σχόλια

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) μέθοδος

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Παράμετροι

| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Διαδρομή προς το βιβλίο εργασίας προορισμού |
| updateChartData | **bool** | Εάν η τιμή είναι false, θα ενημερωθεί μόνο η διαδρομή του βιβλίου εργασίας. [Chart](../../chart/) τα δεδομένα δεν θα φορτωθούν και δεν θα ενημερωθούν από το βιβλίο εργασίας προορισμού. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας προορισμού δεν υπάρχει ή δεν είναι διαθέσιμο. Εάν η τιμή είναι true, τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού. |
## Σχόλια

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)