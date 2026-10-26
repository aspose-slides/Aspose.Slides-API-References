---
title: PdfAccessPermissions
second_title: Référence de l'API Aspose.Slides pour C++
description: Contient un ensemble de drapeaux spécifiant les autorisations d'accès à accorder lorsque le document est ouvert avec un accès utilisateur.
type: docs
weight: 989
url: /fr/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Contient un ensemble de drapeaux spécifiant les autorisations d'accès à accorder lorsque le document est ouvert avec un accès utilisateur.

```cpp
enum class PdfAccessPermissions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Spécifie qu'un utilisateur ne possède pas d'autorisations d'accès. |
| PrintDocument | 4 | Spécifie si un utilisateur peut imprimer le document (éventuellement pas au niveau de qualité le plus élevé, selon que le bit [PdfAccessPermissions::HighQualityPrint](./) est également activé). |
| ModifyContent | 8 | Spécifie si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Spécifie si un utilisateur peut copier ou extraire autrement du texte et des graphiques du document par des opérations autres que celles contrôlées par le bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Spécifie si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs, et, si le bit [PdfAccessPermissions::ModifyContent](./) est également activé, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
| FillExistingFields | 256 | Spécifie si un utilisateur peut remplir des champs de formulaire interactifs existants (y compris les champs de signature), même si le bit [PdfAccessPermissions::AddOrModifyFields](./) est désactivé. |
| ExtractTextAndGraphics | 512 | Spécifie si un utilisateur peut extraire du texte et des graphiques afin de favoriser l'accessibilité pour les utilisateurs handicapés ou à d'autres fins. |
| AssembleDocument | 1024 | Spécifie si un utilisateur peut assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si le bit [PdfAccessPermissions::ModifyContent](./) est désactivé. |
| HighQualityPrint | 2048 | Spécifie si un utilisateur peut imprimer le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit [PdfAccessPermissions::PrintDocument](./) est activé), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |

## Voir également

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)