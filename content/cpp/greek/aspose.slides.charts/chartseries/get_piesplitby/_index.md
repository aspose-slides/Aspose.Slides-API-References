---
title: get_PieSplitBy()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα τύπου πίτα-εντός-πίτας ή μπάρα-εντός-πίτας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – πρόκειται για προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα get_ParentSeriesGroup()->get(set)_PieSplitBy() με δυνατότητα ανάγνωσης/εγγραφής για αλλαγή τιμής. Μόνο για ανάγνωση PieSplitType.
type: docs
weight: 755
url: /el/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() μέθοδος


Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στο δεύτερο πίτα ή μπάρα σε γράφημα τύπου πίτα-εντός-πίτας ή μπάρα-εντός-πίτας. Αυτή είναι η ιδιότητα όχι μόνο αυτής της σειράς αλλά και όλων των σειρών της γονικής ομάδας σειρών – πρόκειται για προβολή της αντίστοιχης ιδιότητας της ομάδας. Συνεπώς αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() με δυνατότητα ανάγνωσης/εγγραφής για να αλλάξετε την τιμή. Μόνο για ανάγνωση [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Παρατηρήσεις


1) Αυτή είναι η προβολή της ιδιότητας [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Εάν η τιμή της ιδιότητας είναι [PieSplitType::Custom](../../piesplittype/), τότε μπορείτε να ορίσετε προσαρμοσμένες πληροφορίες διαχωρισμού με την ιδιότητα [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Δείτε επίσης

* Απαρίθμηση [PieSplitType](../../piesplittype/)
* Κλάση [ChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)