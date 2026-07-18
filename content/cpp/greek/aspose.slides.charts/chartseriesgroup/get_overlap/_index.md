---
title: get_Overlap()
second_title: Aspose.Slides για C++ API Reference
description: Καθορίζει το πόσο θα επικαλύπτονται τα μπαρ και οι στήλες σε διαγράμματα 2-D, ως ποσοστό (από -100% έως 100%).
type: docs
weight: 157
url: /el/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() μέθοδος


Καθορίζει πόσο τα μπαρ και οι στήλες θα αλληλοεπικαλύπτονται σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Παρατηρήσεις


* -100%: Μέγιστο διάστημα (τα μπαρ είναι εντελώς διαχωρισμένα).
* 0%: Τα μπαρ τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή διάστημα.
* 100%: Μέγιστη επικάλυψη (τα μπαρ επικαλύπτονται πλήρως το ένα το άλλο). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int8_t**.



Το παρακάτω παράδειγμα παρουσιάζει πώς να ορίσετε την επικάλυψη για μια ομάδα σειράς διαγράμματος και να αποδώσετε το προκύπτον διάγραμμα σε μια φόρμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Ορίστε την επικάλυψη στο 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Δείτε επίσης

* Κλάση [ChartSeriesGroup](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)