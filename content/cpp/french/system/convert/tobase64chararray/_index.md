---
title: ToBase64CharArray()
second_title: Référence de l'API Aspose.Slides pour C++
description: Base-64 encode une plage d'éléments dans le tableau d'octets spécifié et stocke les données encodées sous forme d'un tableau de caractères Unicode.
type: docs
weight: 27
url: /fr/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method

Base-64 encode une plage d'éléments dans le tableau d'octets spécifié et stocke les données encodées sous forme d'un tableau de caractères Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets contenant la plage d'éléments à encoder |
| offset_in | int | Un index d'un élément dans le tableau d'entrée où commence la plage à encoder |
| length | int | La longueur de la plage d'éléments à encoder |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Une référence constante au tableau de sortie dans lequel les données résultantes doivent être placées |
| offset_out | int | Un index dans le tableau de sortie où commencer à placer les données résultantes |
| insert_line_breaks | **bool** | Spécifie si les caractères de saut de ligne doivent être insérés dans le tableau de sortie après chaque 76 caractères base-64 |

### Valeur de retour

Le nombre de caractères écrits dans le tableau de sortie

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method

Base-64 encode une plage d'éléments dans le tableau d'octets spécifié et stocke les données encodées sous forme d'un tableau de caractères Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets contenant la plage d'éléments à encoder |
| offset_in | int | Un index d'un élément dans le tableau d'entrée où commence la plage à encoder |
| length | int | La longueur de la plage d'éléments à encoder |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Une référence constante au tableau de sortie dans lequel les données résultantes doivent être placées |
| offset_out | int | Un index dans le tableau de sortie où commencer à placer les données résultantes |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Spécifie les options de mise en forme des données encodées en base-64 |

### Valeur de retour

Le nombre de caractères écrits dans le tableau de sortie

## Voir aussi

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)