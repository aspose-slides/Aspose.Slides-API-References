---
title: ToString()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit toutes les valeurs du tableau d'octets spécifié en leur représentation hexadécimale sous forme de chaîne. La casse des lettres à utiliser dans la notation hexadécimale ainsi que le séparateur inséré entre chaque paire d'octets voisins sont spécifiés via les arguments correspondants.
type: docs
weight: 157
url: /fr/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) méthode


Convertit toutes les valeurs du tableau d'octets spécifié en leur représentation hexadécimale sous forme de chaîne. La casse des lettres à utiliser dans la notation hexadécimale ainsi que le séparateur inséré entre chaque paire d'octets voisins sont spécifiés via les arguments correspondants.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| uppercase | **bool** | Spécifie la casse des lettres à utiliser dans la représentation hexadécimale résultante |
| separator | const [String](../../string/)\& | Une chaîne utilisée comme séparateur insérée entre chaque paire d'octets voisins dans la chaîne résultante |

### Valeur de retour

[String](../../string/) contenant la représentation hexadécimale du tableau d'octets spécifié

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) méthode


Convertit les valeurs du tableau d'octets spécifié en leur représentation hexadécimale à partir de l'index spécifié.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau spécifié à partir duquel commencer la conversion |

### Valeur de retour

[String](../../string/) contenant la représentation hexadécimale de la plage d'éléments spécifiée du tableau spécifié

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) méthode


Convertit une plage de valeurs du tableau d'octets spécifié en leur représentation hexadécimale.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau spécifié à partir duquel la plage d'éléments du tableau d'octets à convertir commence |
| length | int | La longueur de la plage des éléments du tableau d'octets à convertir |

### Valeur de retour

[String](../../string/) contenant la représentation hexadécimale de la plage d'éléments spécifiée du tableau spécifié

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)