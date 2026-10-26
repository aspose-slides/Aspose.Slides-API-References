---
title: SetEmbeddedData()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.
type: docs
weight: 248
url: /el/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) μέθοδος

Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Ενσωματωμένα δεδομένα [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Σχόλια

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντικατοπτρίζει τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. 



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
* Κλάση [OleObjectFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)