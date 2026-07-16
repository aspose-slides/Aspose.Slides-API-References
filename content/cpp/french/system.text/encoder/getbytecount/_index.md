---
title: GetByteCount()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Obtient le nombre d'octets nécessaires pour encoder un tampon."
type: docs
weight: 40
url: /fr/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) méthode


Obtient le nombre d'octets nécessaires pour encoder un tampon.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caractères à encoder. |
| index | int | [Buffer](../../../system/buffer/) décalage. |
| count | int | Nombre de caractères à encoder. |
| flush | **bool** | Si true, nettoie l'état interne de l'encodeur après le calcul. |

### Valeur de retour

Nombre d'octets requis pour encoder le tampon.

## Encoder::GetByteCount(const char_t *, int, bool) méthode


Obtient le nombre d'octets nécessaires pour encoder un tampon.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caractères à encoder. |
| count | int | Nombre de caractères à encoder. |
| flush | **bool** | Si true, nettoie l'état interne de l'encodeur après le calcul. |

### Valeur de retour

Nombre d'octets requis pour encoder le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)