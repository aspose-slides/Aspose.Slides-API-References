---
title: SetEmbeddedData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit les informations sur les données OLE incorporées.
type: docs
weight: 248
url: /fr/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) méthode

Définit les informations sur les données OLE incorporées.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Données incorporées [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Remarques

Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est incorporé. 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [OleObjectFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)