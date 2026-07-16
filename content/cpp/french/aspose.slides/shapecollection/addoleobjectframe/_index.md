---
title: AddOleObjectFrame()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes.
type: docs
weight: 183
url: /fr/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) méthode

Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Les informations sur les données OLE intégrées ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## Remarques

L'exemple suivant montre comment ajouter des cadres d'objets OLE à [Slides](../../) de PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Accède à la première diapositive
auto slide = pres->get_Slides()->idx_get(0);
// Charge un fichier Excel dans le flux
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Crée un objet de données pour l'intégration
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Ajoute une forme de cadre d'objet Ole
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Écrit le fichier PPTX sur le disque
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) méthode

Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| className | [System::String](../../../system/string/) | Le nom de classe de l'objet OLE. |
| path | [System::String](../../../system/string/) | Le chemin du fichier lié. |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## Remarques

Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [ShapeCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)