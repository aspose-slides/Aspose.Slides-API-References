---
title: UpdateDocumentProperties()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Ενημερώνει τις ιδιότητες της δεσμευμένης παρουσίασης.
type: docs
weight: 92
url: /el/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) μέθοδος

Ενημερώνει τις ιδιότητες της δεσμευμένης παρουσίασης.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Ιδιότητες εγγράφου [IDocumentProperties](../../idocumentproperties/) |
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει πώς να καλέσετε τη [IPresentationInfo::UpdateDocumentProperties](./) μέθοδο για να ενημερώσετε τις ιδιότητες εγγράφου που επιστρέφονται από την κλήση της [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) μέθοδος.
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
* Κλάση [IPresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)