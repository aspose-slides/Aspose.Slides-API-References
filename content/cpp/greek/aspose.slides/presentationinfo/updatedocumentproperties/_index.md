---
title: UpdateDocumentProperties()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης.
type: docs
weight: 92
url: /el/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) μέθοδος

Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Σχόλια

Αυτό το παράδειγμα δείχνει πώς να καλέσετε τη μέθοδο [PresentationInfo::UpdateDocumentProperties](./) για να ενημερώσετε τις ιδιότητες του εγγράφου που επιστρέφονται από την κλήση της μεθόδου [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/).

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDocumentProperties](../../idocumentproperties/)
* Κλάση [PresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)