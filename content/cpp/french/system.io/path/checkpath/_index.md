---
title: CheckPath()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le chemin spécifié est valide en vérifiant s'il contient des caractères invalides. Une exception est levée si le chemin contient des caractères invalides.
type: docs
weight: 209
url: /fr/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) méthode


Détermine si le chemin spécifié est valide en vérifiant s’il contient des caractères invalides. Une exception est levée si le chemin contient des caractères invalides.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin à vérifier |
| msg | const [String](../../../system/string/)\& | Le message à passer au constructeur de l'objet d'exception |
| allow_empty | **bool** | Spécifie si une chaîne vide ou nulle doit être considérée comme un chemin correct (true) ou non (false) ; si ce paramètre est false et que **path** est vide, une ArgumentException est levée ; si ce paramètre est false et que **path** est nul, une ArgumentNullException est levée |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [Path](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)