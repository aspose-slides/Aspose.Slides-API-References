---
title: get_Categories()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αποκτά τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν IChartData::set_UseSecondaryCategories οριστεί σε false). Μόνο για ανάγνωση IChartCategoryCollection."
type: docs
weight: 40
url: /el/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() μέθοδος


Αποκτά τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε false). Μόνο για ανάγνωση [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Παρατηρήσεις


Εάν [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε false τότε [IChartData::get_SecondaryCategories](../get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [IChartData::get_Categories](./) χρησιμοποιούνται και για τις κύριες και για τις δευτερεύουσες σειρές. Εάν [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) οριστεί σε true τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](../get_secondarycategories/) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](./) χρησιμοποιούνται για τις κύριες σειρές. 

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