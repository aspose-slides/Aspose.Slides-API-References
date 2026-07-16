---
title: ToSingle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit quatre octets du tableau spécifié à partir de l'index indiqué en valeur à virgule flottante simple précision.
type: docs
weight: 131
url: /fr/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) méthode

Convertit quatre octets du tableau spécifié à partir de l’index indiqué en valeur à virgule flottante simple précision.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur à virgule flottante simple précision résultant de la conversion

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) méthode

Convertit quatre octets du tableau spécifié à partir de l’index indiqué en valeur à virgule flottante simple précision.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Valeur de retour

Valeur à virgule flottante simple précision résultant de la conversion

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)