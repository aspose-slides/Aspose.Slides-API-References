---
title: get_SecondaryCategories()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Λαμβάνει τις δευτερεύουσες κατηγορίες εάν ChartData::get_UseSecondaryCategories είναι αληθές. Μόνο για ανάγνωση IChartCategoryCollection."
type: docs
weight: 79
url: /el/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() μέθοδος

Λαμβάνει τις δευτερεύουσες κατηγορίες εάν [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) είναι αληθές. Μόνο για ανάγνωση [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Παρατηρήσεις

Εάν το [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε ψευδές, τότε το [ChartData::get_SecondaryCategories](./) επιστρέφει null και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν το [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε αληθές, τότε τα δεδομένα στο [ChartData::get_SecondaryCategories](./) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στο [ChartData::get_Categories](../get_categories/) χρησιμοποιούνται για κύριες σειρές.

Παράδειγμα. Ποιες κατηγορίες σχετίζονται με τις σειρές - [ChartData::get_Categories](../get_categories/) ή [ChartData::get_SecondaryCategories](./);
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // σχετιζόμενες κατηγορίες είναι series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // σχετιζόμενες κατηγορίας είναι series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartCategoryCollection](../../ichartcategorycollection/)
* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)