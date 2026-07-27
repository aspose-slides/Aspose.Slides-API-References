---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.
type: docs
weight: 339
url: /pt/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() método


Determina se [Aspose.Slides](../../) excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Observações


Os tipos dos objetos binários incorporados:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Leia **bool**. 

O padrão é **false**. 

O exemplo a seguir mostra como carregar a apresentação sem nenhum objeto binário incorporado. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Ver Também

* Classe [ILoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)