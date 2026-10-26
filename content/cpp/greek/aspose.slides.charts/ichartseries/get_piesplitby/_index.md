---
title: get_PieSplitBy()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στο δεύτερο κομμάτι ή μπάρα σε διάγραμμα πίτας-πίτας ή μπάρας-πίτας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – πρόκειται για προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα get_ParentSeriesGroup()->get(set)_PieSplitBy() ανάγνωση/εγγραφή για αλλαγή της τιμής. Μόνο ανάγνωση PieSplitType.
type: docs
weight: 729
url: /el/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() μέθοδος

Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στο δεύτερο κομμάτι ή μπάρα σε διάγραμμα πίτας-πίτας ή μπάρας-πίτας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών - πρόκειται για προβολή της αντίστοιχης ιδιότητας της ομάδας. Έτσι, αυτή η ιδιότητα είναι μόνο ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() ανάγνωση/εγγραφή για την αλλαγή της τιμής. Μόνο ανάγνωση [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Παρατηρήσεις

1) Αυτή είναι η προβολή της ιδιότητας [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Εάν η τιμή της ιδιότητας είναι [PieSplitType::Custom](../../piesplittype/) τότε μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Δείτε επίσης

* Enum [PieSplitType](../../piesplittype/)
* Κλάση [IChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)