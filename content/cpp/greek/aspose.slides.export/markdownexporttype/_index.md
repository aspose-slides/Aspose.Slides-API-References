---
title: MarkdownExportType
second_title: Αναφορά API του Aspose.Slides για C++
description: Τύπος απόδοσης εγγράφου.
type: docs
weight: 950
url: /el/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

Τύπος απόδοσης εγγράφου.

```cpp
enum class MarkdownExportType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Sequential | 0 | Απόδοση όλων των στοιχείων ξεχωριστά. Ένα-ένα. |
| TextOnly | 1 | Απόδοση μόνο κειμένου. |
| Visual | 2 | Απόδοση όλων των στοιχείων, των στοιχείων που έχουν ομαδοποιηθεί - απόδοση μαζί. |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)