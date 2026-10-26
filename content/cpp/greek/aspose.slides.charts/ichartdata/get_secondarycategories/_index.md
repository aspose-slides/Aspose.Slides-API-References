---
title: get_SecondaryCategories()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αποκτά τις δευτερεύουσες κατηγορίες εάν IChartData::get_UseSecondaryCategories είναι αληθές. Μόνο για ανάγνωση IChartCategoryCollection."
type: docs
weight: 79
url: /el/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() μέθοδος

Παίρνει τις δευτερεύουσες κατηγορίες εάν [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) είναι αληθές. Μόνο για ανάγνωση [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Παρατηρήσεις

Εάν [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) είναι ορισμένο σε ψευδές τότε [IChartData::get_SecondaryCategories](./) επιστρέφει null και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται και για τις κύριες και για τις δευτερεύουσες σειρές. Εάν [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) είναι ορισμένο σε αληθές τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](./) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](../get_categories/) χρησιμοποιούνται για τις κύριες σειρές.

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartCategoryCollection](../../ichartcategorycollection/)
* Κλάση [IChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)