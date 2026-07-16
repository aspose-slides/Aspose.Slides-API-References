---
title: HexUnescape()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la représentation hexadécimale spécifiée d'un caractère en caractère.
type: docs
weight: 443
url: /fr/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) méthode

Convertit la représentation hexadécimale spécifiée d'un caractère en caractère.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Une chaîne contenant la représentation hexadécimale d'un caractère |
| index | **int32_t**\& | La position dans **pattern** où commence la représentation hexadécimale d'un caractère |

### Valeur de retour

Le caractère représenté par le codage hexadécimal à la position **index**. Si le caractère à **index** n'est pas encodé en hexadécimal, le caractère à **index** est renvoyé. La valeur de **index** est incrémentée pour pointer vers le caractère suivant celui renvoyé.

## Voir aussi

* Classe [String](../../string/)
* Classe [Uri](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)