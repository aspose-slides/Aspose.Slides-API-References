---
title: set_RootDirectoryClsid()
second_title: Référence API Aspose.Slides pour C++
description: Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /fr/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) méthode

Représente le GUID de classe d'objet (CLSID) qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM de l'application du document. La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
```

## Remarques


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```



## Voir aussi

* Classe [Guid](../../../system/guid/)
* Classe [PptOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)