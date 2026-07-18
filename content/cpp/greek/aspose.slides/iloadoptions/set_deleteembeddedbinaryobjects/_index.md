---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.
type: docs
weight: 352
url: /el/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) μέθοδος


Καθορίζει εάν [Aspose.Slides](../../) θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Παρατηρήσεις


Οι τύποι των ενσωματωμένων δυαδικών αντικειμένων:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object ενσωματωμένα δεδομένα [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) δυαδικά δεδομένα [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Γράψτε **bool**. 

Η προεπιλογή είναι **false**. 

Το παρακάτω παράδειγμα δείχνει πώς να φορτώσετε την παρουσίαση χωρίς κανένα ενσωματωμένο δυαδικό αντικείμενο. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Δείτε επίσης

* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)