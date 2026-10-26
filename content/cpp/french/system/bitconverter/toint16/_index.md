---
title: ToInt16()
second_title: Référence API Aspose.Slides pour C++
description: Convertit deux octets du tableau spécifié à partir de l'index spécifié en valeur entière de 16 bits.
type: docs
weight: 53
url: /fr/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method

Convertit deux octets du tableau spécifié à partir de l'index spécifié en valeur entière de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Return Value

Valeur entière de 16 bits résultant de la conversion

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method

Convertit deux octets du tableau spécifié à partir de l'index spécifié en valeur entière de 16 bits.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel commencer à prendre les octets pour la conversion |

### Return Value

Valeur entière de 16 bits résultant de la conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [BitConverter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)