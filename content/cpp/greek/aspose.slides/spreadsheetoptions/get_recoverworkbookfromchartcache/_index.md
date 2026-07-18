---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από τη λανθάνουσα μνήμη του γραφήματος.
type: docs
weight: 27
url: /el/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() μέθοδος


Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από τη λανθάνουσα μνήμη του γραφήματος.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

* Κλάση [SpreadsheetOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)