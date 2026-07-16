---
title: RemoveScriptFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la configuration de police associée à une balise de script spécifique de la collection de polices du thème.
type: docs
weight: 118
url: /fr/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) méthode


Supprime la configuration de police associée à une balise de script spécifique de la collection de polices du thème.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Le code de script BCP-47 dont la configuration de police doit être supprimée. |
## Remarques



Cet exemple montre comment supprimer le mappage de police pour le script hébreu : 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)