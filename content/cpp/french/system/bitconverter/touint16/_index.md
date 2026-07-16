---
title: ToUInt16()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit deux octets du tableau spécifié à partir de l'index indiqué en une valeur entière non signée de 16 bits.
type: docs
weight: 92
url: /fr/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) method


Convertit deux octets du tableau spécifié à partir de l'index indiqué en une valeur entière non signée de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel prendre les octets pour la conversion |

### Valeur de retour

Valeur entière non signée de 16 bits résultant de la conversion

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method


Convertit deux octets du tableau spécifié à partir de l'index indiqué en une valeur entière non signée de 16 bits.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView qui contient les octets à convertir |
| startIndex | int | Index dans le tableau à partir duquel prendre les octets pour la conversion |

### Valeur de retour

Valeur entière non signée de 16 bits résultant de la conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)