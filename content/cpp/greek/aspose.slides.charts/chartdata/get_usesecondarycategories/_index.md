---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αν οριστεί σε false τότε ChartData::get_SecondaryCategories επιστρέφει null και τα δεδομένα στο ChartData::get_Categories χρησιμοποιούνται τόσο για τις πρωτεύουσες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο ChartData::get_SecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο ChartData::get_Categories χρησιμοποιούνται για τις πρωτεύουσες σειρές. Ανάγνωση bool."
type: docs
weight: 53
url: /el/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() μέθοδος


Αν οριστεί σε false, τότε το [ChartData::get_SecondaryCategories](../get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται τόσο για τις πρωτεύουσες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true, τότε τα δεδομένα στο [ChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται για τις πρωτεύουσες σειρές. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Σχόλια


Παράδειγμα. Ποιες κατηγορίες σχετίζονται με τις σειρές - [ChartData::get_Categories](../get_categories/) ή [ChartData::get_SecondaryCategories](../get_secondarycategories/); 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // σχετικές κατηγορίες είναι series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // σχετικές κατηγορίες είναι series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Δείτε επίσης

* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)