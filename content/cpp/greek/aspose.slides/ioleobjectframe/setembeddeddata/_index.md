---
title: SetEmbeddedData()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.
type: docs
weight: 248
url: /el/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) μέθοδος

Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Ενσωματωμένα δεδομένα [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Παρατηρήσεις

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο.

Το παρακάτω παράδειγμα δείχνει πώς να αλλάξετε τα ενσωματωμένα δεδομένα OLE και τον τύπο τους για υπάρχον αντικείμενο [IOleObjectFrame](../) 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Κλάση [IOleObjectFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)