---
title: ToInt64()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit huit octets du tableau spécifié à partir de l'indice spécifié en une valeur entière 64-bit.
type: docs
weight: 79
url: /fr/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) method


Convertit huit octets du tableau spécifié à partir de l’indice spécifié en une valeur entière 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Indice dans le tableau où commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur entière 64 bits résultant de la conversion

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method


Convertit huit octets du tableau spécifié à partir de l’indice spécifié en une valeur entière 64 bits.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Indice dans le tableau où commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur entière 64 bits résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)