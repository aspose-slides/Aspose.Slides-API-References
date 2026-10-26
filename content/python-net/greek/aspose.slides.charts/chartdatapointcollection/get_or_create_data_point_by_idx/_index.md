---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Αν η συλλογή περιέχει ήδη σημείο δεδομένων με δείκτη `index`, τότε επιστρέφει αυτό το σημείο δεδομένων.
Αν η συλλογή δεν περιέχει σημείο δεδομένων με δείκτη `index`==N
(όταν ο αριθμός των σημείων δεδομένων σε αυτή τη συλλογή είναι μικρότερος ή ίσος με N)
τότε προσθέτει ελλιπή σημεία δεδομένων και επιστρέφει το τελευταίο (που έχει τον ζητούμενο δείκτη).
Για παράδειγμα, οι δείκτες της συλλογής είναι {0, 1, 2}, και ο ζητούμενος δείκτης είναι 5.
Τότε η μέθοδος προσθέτει ελλιπή σημεία δεδομένων: {0, 1, 2, 3, 4, 5}. Και επιστρέφει το σημείο δεδομένων με δείκτη 5.

### Επιστρέφει

Επιστρέφει το σημείο δεδομένων με το ζητούμενο δείκτη.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Δείκτης. |



### Δείτε επίσης
* κλάση [`ChartDataPointCollection`](/slides/python-net/el/aspose.slides.charts/chartdatapointcollection)
* κλάση [`IChartDataPoint`](/slides/python-net/el/aspose.slides.charts/ichartdatapoint)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)