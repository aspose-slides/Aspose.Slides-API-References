---
title: categories property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories ιδιότητα
Λαμβάνει τις κύριες κατηγορίες (ή τόσο τις κύριες όσο και τις δευτερεύουσες κατηγορίες αν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι ψευδής).
Μόνο-ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection).

### Παρατηρήσεις

Αν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι ψευδής τότε η ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) επιστρέφει None και τα δεδομένα σε αυτήν την ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται και για τις κύριες και για τις δευτερεύουσες σειρές.
Αν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι αληθής τότε τα δεδομένα στην ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα σε αυτήν την ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται για τις κύριες σειρές.

### Ορισμός:
```python
@property
def categories(self):
    ...
```

### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* κλάση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)