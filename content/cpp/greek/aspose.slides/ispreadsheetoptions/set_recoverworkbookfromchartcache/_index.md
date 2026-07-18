---
title: set_RecoverWorkbookFromChartCache()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από τη λανθάνουσα μνήμη του διαγράμματος.
type: docs
weight: 40
url: /el/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) μέθοδος


Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό αρχείο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από τη λανθάνουσα μνήμη του διαγράμματος.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Δείτε επίσης

* Κλάση [ISpreadsheetOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)