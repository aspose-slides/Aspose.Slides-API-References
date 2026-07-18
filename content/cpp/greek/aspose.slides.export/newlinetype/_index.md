---
title: NewLineType
second_title: Aspose.Slides για την αναφορά API C++
description: Τύπος νέας γραμμής που θα χρησιμοποιηθεί στο δημιουργημένο έγγραφο.
type: docs
weight: 963
url: /el/aspose.slides.export/newlinetype/
---
## NewLineType enum

Τύπος νέας γραμμής που θα χρησιμοποιηθεί στο δημιουργημένο έγγραφο.

```cpp
enum class NewLineType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS νέα γραμμή - \r\n |
| Unix | 1 | Unix & Mac OS X νέα γραμμή - \n |
| Mac | 2 | Mac (OS 9) νέα γραμμή - \r |

## Σχόλια

Παράδειγμα 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)