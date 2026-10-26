---
title: get_NumberFormat()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Διαβάστε System::String."
type: docs
weight: 27
url: /el/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() μέθοδος


Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Διαβάστε [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Παρατηρήσεις



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Εάν ο γονέας αυτού του αντικειμένου [DataLabelFormat](../../datalabelformat/) είναι μια συλλογή [DataLabelCollection](../../datalabelcollection/) ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή [DataLabelCollection](../../datalabelcollection/). Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, η τιμή αυτή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή [DataLabelCollection](../../datalabelcollection/) (π.χ. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" προκαλεί όλες τις DataLabels[i].NumberFormat να ισούται με val). 
## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IDataLabelFormat](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)