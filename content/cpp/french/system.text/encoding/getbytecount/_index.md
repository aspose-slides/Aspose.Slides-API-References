---
title: GetByteCount()
second_title: Référence API Aspose.Slides for C++
description: Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.
type: docs
weight: 235
url: /fr/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) méthode

Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tampon de caractères. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Taille de tampon requise.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) méthode

Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tampon de caractères. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Taille de tampon requise.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) méthode

Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tampon de caractères. |
| index | int | Début de la tranche. |
| count | int | Taille de la tranche. |

### Valeur de retour

Taille de tampon requise.

## Encoding::GetByteCount(const String\&) méthode

Obtient le nombre de caractères nécessaires pour encoder une chaîne.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) à encoder. |

### Valeur de retour

Taille de tampon requise.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) méthode

Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tampon de caractères. |

### Valeur de retour

Taille de tampon requise.

## Encoding::GetByteCount(const char_t *, int) méthode

Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tampon de caractères. |
| count | int | [Buffer](../../../system/buffer/) taille. |

### Valeur de retour

Taille de tampon requise.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)