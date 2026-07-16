---
title: GetByteCount()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères.
type: docs
weight: 27
url: /fr/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) méthode


Obtenir le nombre de caractères nécessaires pour encoder un tampon de caractères.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tampon de caractères. |
| count | int | [Buffer](../../../system/buffer/) taille. |

### Valeur de retour

Taille du tampon requise.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) méthode


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) méthode


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) méthode


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) méthode


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) méthode


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) méthode


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)