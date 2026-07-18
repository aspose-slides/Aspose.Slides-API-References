---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides για C++ API Reference
description: Λαμβάνει τη λειτουργία κατά την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. Αυτή η ιδιότητα δεν υποστηρίζει την εκχώρηση αντικειμένων τύπου Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 391
url: /el/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() μέθοδος

Λαμβάνει τη λειτουργία κατά την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../islideslayoutoptions/). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Κλάση [ISwfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)