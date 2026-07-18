---
title: set_NumberFormat()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αναπαριστά τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Γράψτε System::String."
type: docs
weight: 40
url: /el/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) μέθοδος

Αναπαριστά τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Γράψτε [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```
## Παρατηρήσεις

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Εάν ο γονέας αυτού του αντικειμένου [DataLabelFormat](../../datalabelformat/) είναι μια [DataLabelCollection](../../datalabelcollection/) συλλογή ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή [DataLabelCollection](../../datalabelcollection/). Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, αυτή η τιμή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή [DataLabelCollection](../../datalabelcollection/) (π.χ. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" προκαλεί όλες τις DataLabels[i].NumberFormat να ισούται με val). 
## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IDataLabelFormat](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)