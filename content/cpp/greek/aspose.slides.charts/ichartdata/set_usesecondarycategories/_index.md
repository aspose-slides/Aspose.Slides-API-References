---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αν οριστεί σε false τότε IChartData::get_SecondaryCategories επιστρέφει null και τα δεδομένα στο IChartData::get_Categories χρησιμοποιούνται τόσο για τις πρωτεύουσες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο IChartData::get_SecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο IChartData::get_Categories χρησιμοποιούνται για τις πρωτεύουσες σειρές. Γράψτε bool."
type: docs
weight: 66
url: /el/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) μέθοδος


Αν οριστεί σε false τότε [IChartData::get_SecondaryCategories](../get_secondarycategories/) returns null και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται για τις πρωτεύουσες σειρές. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Παρατηρήσεις


Παράδειγμα. Ποιες κατηγορίες σχετίζονται με τις σειρές - ChartData.Categories ή ChartData.SecondaryCategories;
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

* Κλάση [IChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)