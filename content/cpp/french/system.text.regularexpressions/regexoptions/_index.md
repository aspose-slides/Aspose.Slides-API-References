---
title: RegexOptions
second_title: Référence de l'API Aspose.Slides pour C++
description: Options d'expression régulière.
type: docs
weight: 118
url: /fr/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum

[Regex](../regex/) options.

```cpp
enum class RegexOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Comportement par défaut. |
| Compiled | 1 | Compile la regex pour les performances. Toujours fait par défaut. |
| CultureInvariant | 2 | Utiliser la correspondance indépendante de la culture. Ignoré. |
| ECMAScript | 4 | Utiliser la syntaxe ECMAScript. Ignoré. |
| ExplicitCapture | 8 | Capture explicite uniquement. Ignoré. |
| IgnoreCase | 16 | Ignorer la casse lors de la correspondance. |
| IgnorePatternWhitespace | 32 | Ignorer les espaces blancs dans le modèle. Non pris en charge. |
| Multiline | 64 | Traiter '^' et '$' comme le début et la fin de la ligne, pas de la chaîne entière. |
| RightToLeft | 128 | Correspondance de droite à gauche. Non pris en charge. |
| Singleline | 256 | Faire en sorte que '.' corresponde à n'importe quel caractère sans exception (normalement, les caractères de nouvelle ligne ne sont pas correspondants). |

## Voir aussi

* Espace de noms [System::Text::RegularExpressions](../)
* Bibliothèque [Aspose.Slides](../../)