---
title: SetScriptFont()
second_title: Référence API Aspose.Slides pour C++
description: Assigne un nom de police à une balise de script spécifique, ce qui définit la manière dont le texte de ce script sera rendu dans la présentation.
type: docs
weight: 105
url: /fr/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) méthode

Assigne un nom de police à une balise de script spécifique, ce qui définit la manière dont le texte de ce script sera rendu dans la présentation.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Le code de script BCP-47 (par ex., "Arab", "Hebr", "Hans") identifiant le système d'écriture. |
| fontName | [System::String](../../../system/string/) | Le nom de la police à attribuer au script spécifié. |
## Remarques

Cet exemple montre comment définir la police pour le script arabe sur "Segoe UI" :
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)