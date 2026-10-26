---
title: set_Overlap()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει πόσο θα επικαλύπτονται οι μπάρες και οι στήλες σε 2-Δ διαγράμματα, ως ποσοστό (από -100% έως 100%).
type: docs
weight: 196
url: /el/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) μέθοδος

Καθορίζει το πόσο τα μπάρα και οι στήλες θα επικαλύπτονται σε 2-D διαγράμματα, ως ποσοστό (από -100% έως 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Σχόλια

* -100%: Μέγιστο διάστημα (τα μπάρα διαχωρίζονται πλήρως).
* 0%: Τα μπάρα τοποθετούνται δίπλα δίπλα χωρίς επικάλυψη ή διάστημα.
* 100%: Μέγιστη επικάλυψη (τα μπάρα επικαλύπτονται πλήρως το ένα το άλλο). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int8_t**.

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε την επικάλυψη για μια ομάδα σειράς διαγράμματος και να αποδώσετε το προκύπτον διάγραμμα σε μια φόρμα:
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

* Κλάση [IChartSeriesGroup](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)