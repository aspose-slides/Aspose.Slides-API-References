---
title: GetScriptFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nom de la police associé à une balise de script spécifique du thème de la présentation.
type: docs
weight: 92
url: /fr/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) méthode


Obtient le nom de la police associé à un balise de script spécifique du thème de la présentation.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Le code de script BCP-47 (ex. \"Latn\", \"Cyrl\", \"Jpan\") utilisé pour identifier un système d’écriture. |

### Return Value

Le nom de la police utilisée pour le script spécifié, ou **null** si le script n’est pas défini.

## Remarques



Cet exemple montre comment récupérer la police assignée au script cyrillique dans le thème de la présentation. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)