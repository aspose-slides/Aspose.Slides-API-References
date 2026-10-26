---
title: ToUInt64()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit huit octets du tableau spécifié à partir de l'index indiqué en valeur entière non signée de 64 bits.
type: docs
weight: 118
url: /fr/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) méthode


Convertit huit octets du tableau spécifié à partir de l'index spécifié en valeur entière non signée de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre des octets pour la conversion |

### Valeur de retour

Valeur entière non signée de 64 bits résultant de la conversion

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) méthode


Convertit huit octets du tableau spécifié à partir de l'index spécifié en valeur entière non signée de 64 bits.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre des octets pour la conversion |

### Valeur de retour

Valeur entière non signée de 64 bits résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)