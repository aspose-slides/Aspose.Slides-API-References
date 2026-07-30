---
title: SetEmbeddedData()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta le informazioni sui dati OLE incorporati.
type: docs
weight: 248
url: /it/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Imposta le informazioni sui dati OLE incorporati.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Dati incorporati [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Osservazioni


Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e imposta il flag IsObjectLink su false, indicando che l'oggetto OLE è incorporato. 


L'esempio seguente dimostra come modificare i dati OLE incorporati e il loro tipo per un oggetto [IOleObjectFrame](../) esistente 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [IOleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)