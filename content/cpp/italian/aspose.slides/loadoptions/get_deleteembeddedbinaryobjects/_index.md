---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.
type: docs
weight: 339
url: /it/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() metodo


Determina se [Aspose.Slides](../../) eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Osservazioni


I tipi degli oggetti binari incorporati:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Lettura **bool**. 

Predefinito è **false**. 

Il seguente esempio mostra come caricare la presentazione senza alcun oggetto binario incorporato. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Vedi anche

* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)