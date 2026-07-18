---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εάν η πηγή δεδομένων για το διάγραμμα είναι ένα εξωτερικό workbook και δεν είναι διαθέσιμη, θα ανακτηθεί από τη μνήμη cache του διαγράμματος.
type: docs
weight: 40
url: /el/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) μέθοδος

Εάν η πηγή δεδομένων για το διάγραμμα είναι ένα εξωτερικό Workbook και δεν είναι διαθέσιμη, θα ανακτηθεί από τη μνήμη cache του διαγράμματος.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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