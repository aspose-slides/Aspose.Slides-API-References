---
title: categories property
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/categories/
weight: 80
---
## κατηγορίες ιδιότητα

Επιστρέφει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι ψευδής).  
Μόνο για ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection).

### Παρατηρήσεις

Εάν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι ψευδής, τότε η ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) επιστρέφει None και τα δεδομένα σε αυτήν την ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται και για τις κύριες και για τις δευτερεύουσες σειρές.  
Εάν η ιδιότητα [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) είναι αληθής, τότε τα δεδομένα στην ιδιότητα [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα σε αυτήν την ιδιότητα [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) χρησιμοποιούνται για τις κύριες σειρές.

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