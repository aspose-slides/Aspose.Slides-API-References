---
title: get_SlidesLayoutOptions()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης ISlidesLayoutOptions. Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου HandoutLayoutingOptions
type: docs
weight: 391
url: /el/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() μέθοδος

Λαμβάνει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα όταν εξάγεται μια παρουσίαση [ISlidesLayoutOptions](../../islideslayoutoptions/). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
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
* Κλάση [SwfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)