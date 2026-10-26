---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει αν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.
type: docs
weight: 339
url: /el/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() μέθοδος


Καθορίζει αν [Aspose.Slides](../../) θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Παρατηρήσεις


Τύποι των ενσωματωμένων δυαδικών αντικειμένων:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) δυαδικά δεδομένα [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Ανάγνωση **bool**. 

Η προεπιλογή είναι **false**. 

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε την παρουσίαση χωρίς κανένα ενσωματωμένο δυαδικό αντικείμενο. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Δείτε επίσης

* Κλάση [ILoadOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)