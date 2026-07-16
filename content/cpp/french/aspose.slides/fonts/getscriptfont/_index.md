---
title: GetScriptFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nom de police associé à une balise de script spécifique du thème de la présentation.
type: docs
weight: 92
url: /fr/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) méthode


Obtient le nom de police associé à une balise de script spécifique du thème de la présentation.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Le code de script BCP-47 (par ex. "Latn", "Cyrl", "Jpan") utilisé pour identifier un système d'écriture. |

### Valeur de retour

Le nom de la police utilisé pour le script spécifié, ou **null** si le script n'est pas défini.
## Remarques



Cet exemple montre comment récupérer la police attribuée au script cyrillique dans le thème de la présentation. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)