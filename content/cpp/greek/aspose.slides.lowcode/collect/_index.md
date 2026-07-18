---
title: Collect
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη συλλογή αντικειμένων μοντέλου διαφορετικών τύπων από Presentation.
type: docs
weight: 1
url: /el/aspose.slides.lowcode/collect/
---
## Collect κλάση

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη συλλογή αντικειμένων μοντέλου διαφορετικών τύπων από [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Συλλέγει όλες τις περιπτώσεις του [Shape](../../aspose.slides/shape/) στο [Presentation](../../aspose.slides/presentation/). |
## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... αλλάξτε τη μορφοποίηση του σχήματος ή άλλες ιδιότητες
}
```

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::LowCode](../)
* Βιβλιοθήκη [Aspose.Slides](../../)