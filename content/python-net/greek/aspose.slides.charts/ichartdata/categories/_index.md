---
title: categories property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories ιδιότητα
Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα [`IChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories) είναι ψευδής). Μόνο για ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection).

### Παρατηρήσεις

Εάν η ιδιότητα [`IChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories) είναι ψευδής, τότε η ιδιότητα [`IChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/secondary_categories) επιστρέφει None και τα δεδομένα σε αυτήν την ιδιότητα [`IChartData.categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/categories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν η ιδιότητα [`IChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/use_secondary_categories) είναι αληθής, τότε τα δεδομένα στην ιδιότητα [`IChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/secondary_categories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα σε αυτήν την ιδιότητα [`IChartData.categories`](/slides/python-net/el/aspose.slides.charts/ichartdata/categories) χρησιμοποιούνται για τις κύριες σειρές.

### Ορισμός:
```python
@property
def categories(self):
    ...
```

### Δείτε επίσης
* κλάση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection)
* κλάση [`IChartData`](/slides/python-net/el/aspose.slides.charts/ichartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)