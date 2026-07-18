---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides για αναφορά API C++
description: Εάν η πηγή δεδομένων για το διάγραμμα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από το cache του διαγράμματος.
type: docs
weight: 27
url: /el/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() μέθοδος


Αν η πηγή δεδομένων για το διάγραμμα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από τη μνήμη cache του διαγράμματος.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
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

## Βλέπε επίσης

* Κλάση [ISpreadsheetOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)