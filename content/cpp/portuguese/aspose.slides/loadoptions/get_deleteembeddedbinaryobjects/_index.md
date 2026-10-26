---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.
type: docs
weight: 339
url: /pt/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() método

Determina se [Aspose.Slides](../../) excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Observações

Os tipos dos objetos binários incorporados:

* Projeto VBA [IPresentation::VbaProject](../)
* dados incorporados do Objeto OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) dados binários [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Ler **bool**.

O padrão é **false**.

O exemplo a seguir mostra como carregar a apresentação sem quaisquer objetos binários incorporados.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Ver também

* Classe [LoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)