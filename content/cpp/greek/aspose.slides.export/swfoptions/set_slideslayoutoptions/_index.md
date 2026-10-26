---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει τη λειτουργία στην οποία τα διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου HandoutLayoutingOptions
type: docs
weight: 404
url: /el/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) μέθοδος

Ορίζει τη λειτουργία στην οποία τα διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../islideslayoutoptions/). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Κλάση [SwfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)