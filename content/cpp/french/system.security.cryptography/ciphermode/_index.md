---
title: CipherMode
second_title: Référence API Aspose.Slides pour C++
description: Mode de chiffrement par bloc.
type: docs
weight: 885
url: /fr/system.security.cryptography/ciphermode/
---
## CipherMode énum

Mode de chiffrement par bloc.

```cpp
enum class CipherMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| CBC | 1 | Chaînage de blocs de chiffrement qui combine le bloc actuel avec le bloc précédent pour améliorer le chiffrement. |
| ECB | 2 | Mode cahier de codes électroniques sans influences inter-blocs ; entraîne un chiffrement plus faible. |
| OFB | 3 | Mode de rétroaction de sortie qui traite les gros blocs d'entrée par petits morceaux. |
| CFB | 4 | Mode de rétroaction de chiffrement qui traite les gros blocs d'entrée par petits morceaux. Les règles de mutilation diffèrent de celles de l'OFB. |
| CTS | 5 | Mode de vol de texte chiffré, se comporte comme le CBC pour tous les blocs sauf les deux derniers du texte. |

## Voir aussi

* Espace de noms [System::Security::Cryptography](../)
* Bibliothèque [Aspose.Slides](../../)