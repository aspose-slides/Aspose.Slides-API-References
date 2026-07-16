---
title: ToBoolean()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit un octet du tableau spécifié en commençant à l'index spécifié en valeur booléenne.
type: docs
weight: 27
url: /fr/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) méthode


Convertit un octet du tableau spécifié en commençant à l'index spécifié en valeur booléenne.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur de retour

[Boolean](../../boolean/) valeur résultant de la conversion

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) méthode


Convertit un octet du tableau spécifié en commençant à l'index spécifié en valeur booléenne.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur de retour

[Boolean](../../boolean/) valeur résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)