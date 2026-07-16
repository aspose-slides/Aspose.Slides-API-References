---
title: LoadExternalFonts()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute des dossiers supplémentaires pour rechercher des polices.
type: docs
weight: 1
url: /fr/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) méthode

Ajoute des dossiers supplémentaires pour rechercher des polices.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Répertoires pour lire des polices supplémentaires. |
## Remarques

L'exemple suivant montre comment charger des polices personnalisées depuis des fichiers .TTF 
```cpp
// Le chemin du répertoire des documents.
System::String dataDir = u"C:\\";
 
// Dossiers pour rechercher les polices
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});
 
// Charger les polices du répertoire de polices personnalisé
FontsLoader::LoadExternalFonts(folders);
 
// Effectuer du travail et rendre la présentation/les diapositives
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);
 
// Effacer le cache des polices
FontsLoader::ClearCache();
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontsLoader](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)