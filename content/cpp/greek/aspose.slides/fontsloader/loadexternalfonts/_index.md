---
title: LoadExternalFonts()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Προσθέτει επιπλέον φακέλους για την εύρεση γραμματοσειρών.
type: docs
weight: 1
url: /el/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) method

Προσθέτει επιπλέον φακέλους για την εύρεση γραμματοσειρών.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Κατάλογοι για ανάγνωση επιπλέον γραμματοσειρών. |
## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε προσαρμοσμένες γραμματοσειρές από .TTF 
```cpp
// Η διαδρομή προς τον φάκελο εγγράφων.
System::String dataDir = u"C:\\";

// φακέλους για την εύρεση γραμματοσειρών
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Φόρτωση των γραμματοσειρών του προσαρμοσμένου καταλόγου γραμματοσειρών
FontsLoader::LoadExternalFonts(folders);

// Πραγματοποιήστε κάποια εργασία και εκτελέστε την απόδοση παρουσίασης/διαφανειών
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Καθαρισμός cache γραμματοσειρών
FontsLoader::ClearCache();
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FontsLoader](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)