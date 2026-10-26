---
title: SetEmbeddedData()
second_title: Referência da API Aspose.Slides para C++
description: Define informações sobre os dados incorporados OLE.
type: docs
weight: 248
url: /pt/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) método

Define informações sobre os dados incorporados OLE.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Dados incorporados [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Observações

Este método altera as propriedades do objeto para refletir os novos dados e define o sinalizador IsObjectLink como false, indicando que o objeto OLE está incorporado. 



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [OleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)