---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Εάν οριστεί σε false τότε IChartData::get_SecondaryCategories επιστρέφει null και τα δεδομένα στο IChartData::get_Categories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν οριστεί σε true τότε τα δεδομένα στο IChartData::get_SecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο IChartData::get_Categories χρησιμοποιούνται για τις κύριες σειρές. Διαβάστε bool."
type: docs
weight: 53
url: /el/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() μέθοδος


Αν οριστεί σε false τότε [IChartData::get_SecondaryCategories](../get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται για τις κύριες σειρές. Διαβάστε **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
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