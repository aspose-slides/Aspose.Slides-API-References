---
title: ToDouble()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit huit octets du tableau spécifié à partir de l'index indiqué en une valeur à virgule flottante double précision.
type: docs
weight: 144
url: /fr/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) méthode


Convertit huit octets du tableau spécifié à partir de l'index indiqué en une valeur à virgule flottante double précision.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur renvoyée

Valeur à virgule flottante double précision résultant de la conversion

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) méthode


Convertit huit octets du tableau spécifié à partir de l'index indiqué en une valeur à virgule flottante double précision.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur renvoyée

Valeur à virgule flottante double précision résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)