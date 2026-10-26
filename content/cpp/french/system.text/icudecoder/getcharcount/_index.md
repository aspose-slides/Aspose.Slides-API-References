---
title: GetCharCount()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nombre de caractères nécessaires pour décoder un tampon.
type: docs
weight: 40
url: /fr/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | [Buffer](../../../system/buffer/) décalage. |
| count | int | Nombre d'octets à décoder. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Octets à décoder. |
| index | int | [Buffer](../../../system/buffer/) décalage. |
| count | int | Nombre d'octets à décoder. |
| flush | **bool** | Si true, nettoie l'état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) méthode


Obtient le nombre de caractères nécessaires pour décoder un tampon.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Octets à décoder. |
| count | int | Nombre d'octets à décoder. |
| flush | **bool** | Si true, nettoie l'état interne du décodeur après le calcul. |

### Valeur de retour

Nombre de caractères requis pour décoder le tampon.

## Voir également

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUDecoder](../)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)