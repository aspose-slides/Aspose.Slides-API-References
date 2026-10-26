---
title: RemoveScriptFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème.
type: docs
weight: 118
url: /fr/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) méthode

Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Le code de script BCP-47 dont le paramètre de police doit être supprimé. |
## Remarques

Cet exemple montre comment supprimer la correspondance de police pour le script hébreu : 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)