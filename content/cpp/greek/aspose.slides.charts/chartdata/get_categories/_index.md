---
title: get_Categories()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αποκτά τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν ChartData::set_UseSecondaryCategories έχει οριστεί σε false). Μόνο για ανάγνωση IChartCategoryCollection."
type: docs
weight: 40
url: /el/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() μέθοδος

Αποκτά τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) έχει οριστεί σε false). Μόνο για ανάγνωση [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Παρατηρήσεις

Εάν [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε false τότε [ChartData::get_SecondaryCategories](../get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [ChartData::get_Categories](./) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε true τότε τα δεδομένα στο [ChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [ChartData::get_Categories](./) χρησιμοποιούνται για τις κύριες σειρές.

Παράδειγμα. Ποιες κατηγορίες σχετίζονται με τις σειρές - [ChartData::get_Categories](./) ή [ChartData::get_SecondaryCategories](../get_secondarycategories/);

```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartCategoryCollection](../../ichartcategorycollection/)
* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)