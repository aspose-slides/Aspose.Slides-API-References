---
title: SetExternalWorkbook()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει εξωτερικό workbook ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το στοχευόμενο workbook.
type: docs
weight: 196
url: /el/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) μέθοδος

Ορίζει εξωτερικό workbook ως πηγή δεδομένων για το διάγραμμα. [Chart](../../chart/) δεδομένα θα ενημερωθούν από το στοχευόμενο workbook.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Διαδρομή προς το στοχευόμενο workbook |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) μέθοδος

Ορίζει εξωτερικό workbook ως πηγή δεδομένων για το διάγραμμα.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Διαδρομή προς το στοχευόμενο workbook |
| updateChartData | **bool** | Αν η τιμή είναι false, θα ενημερωθεί μόνο η διαδρομή του workbook. [Chart](../../chart/) δεδομένα δεν θα φορτωθούν και δεν θα ενημερωθούν από το στοχευόμενο workbook. Μπορεί να χρησιμοποιηθεί όταν το στοχευόμενο workbook δεν υπάρχει ή δεν είναι διαθέσιμο. Αν η τιμή είναι true, τα δεδομένα του chart θα ενημερωθούν από το στοχευόμενο workbook. |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Δείτε επίσης

* Τάξη [String](../../../system/string/)
* Τάξη [IChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)