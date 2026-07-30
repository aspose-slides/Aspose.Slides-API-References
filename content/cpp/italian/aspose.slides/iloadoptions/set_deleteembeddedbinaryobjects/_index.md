---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.
type: docs
weight: 352
url: /it/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) metodo


Determina se [Aspose.Slides](../../) eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Osservazioni


I tipi degli oggetti binari incorporati:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object dati incorporati [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dati binari [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Scrivi **bool**. 

Il valore predefinito è **false**. 

Il seguente esempio mostra come caricare la presentazione senza alcun oggetto binario incorporato. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Vedi anche

* Classe [ILoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)