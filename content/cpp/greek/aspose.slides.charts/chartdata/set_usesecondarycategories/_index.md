---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αν οριστεί σε false τότε ChartData::get_SecondaryCategories επιστρέφει null και τα δεδομένα στο ChartData::get_Categories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο ChartData::get_SecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο ChartData::get_Categories χρησιμοποιούνται για τις κύριες σειρές. Γράψτε bool."
type: docs
weight: 66
url: /el/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) μέθοδος

Αν οριστεί σε false τότε [ChartData::get_SecondaryCategories](../get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν οριστεί σε true τότε τα δεδομένα στο [ChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται για τις κύριες σειρές. Γράψτε **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Παρατηρήσεις

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