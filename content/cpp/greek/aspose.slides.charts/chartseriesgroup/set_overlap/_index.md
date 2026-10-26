---
title: set_Overlap()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει πόσο οι μπάρες και οι στήλες θα επικαλύπτονται σε διαγράμματα 2-Δ, ως ποσοστό (από -100% έως 100%).
type: docs
weight: 170
url: /el/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) μέθοδος

Καθορίζει πόσο οι μπάρες και οι στήλες θα επικαλύπτονται σε 2-D διαγράμματα, ως ποσοστό (από -100% έως 100%).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Παρατηρήσεις

* -100%: Μέγιστο κενό (οι μπάρες είναι πλήρως διαχωρισμένες).
* 0%: Οι μπάρες τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή κενό.
* 100%: Μέγιστη επικάλυψη (οι μπάρες επικαλύπτονται πλήρως μεταξύ τους). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή **int8_t**.

Το ακόλουθο παράδειγμα δείχνει πώς να ορίσετε την επικάλυψη για μια ομάδα σειρών διαγράμματος και να αποδώσετε το παραγόμενο γράφημα σε μια φόρμα: 
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