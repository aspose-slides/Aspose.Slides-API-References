---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.
type: docs
weight: 352
url: /pt/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) método

Determina se [Aspose.Slides](../../) excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Observações

Os tipos dos objetos binários incorporados:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dados binários [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Escreva **bool**. 

O padrão é **false**. 

O exemplo a seguir mostra como carregar a apresentação sem nenhum objeto binário incorporado. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Veja Também

* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)