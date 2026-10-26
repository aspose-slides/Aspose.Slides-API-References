---
title: ToInt32()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit quatre octets du tableau spécifié à partir de l'index indiqué en une valeur entière 32 bits.
type: docs
weight: 66
url: /fr/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) méthode

Convertit quatre octets du tableau spécifié à partir de l'index spécifié en une valeur entière 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau où commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur entière 32 bits résultant de la conversion

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) méthode

Convertit quatre octets du tableau spécifié à partir de l'index spécifié en une valeur entière 32 bits.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau où commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur entière 32 bits résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)