---
title: GetCharCount()
second_title: Référence API Aspose.Slides pour C++
description: Obtient le nombre de caractères nécessaires pour décoder un tampon.
type: docs
weight: 40
url: /fr/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | [Buffer](../../../system/buffer/) décalage. |
| count | int | Nombre d'octets à décoder. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | [Buffer](../../../system/buffer/) décalage. |
| count | int | Nombre d'octets à décoder. |
| flush | **bool** | Si vrai, nettoie l'état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## Decoder::GetCharCount(const uint8_t *, int, bool) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets à décoder. |
| flush | **bool** | Si vrai, nettoie l'état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)