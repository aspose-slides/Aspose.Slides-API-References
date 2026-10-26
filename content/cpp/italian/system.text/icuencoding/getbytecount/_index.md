---
title: GetByteCount()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.
type: docs
weight: 27
url: /it/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) metodo


Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Buffer di caratteri. |
| count | int | [Buffer](../../../system/buffer/) dimensione. |

### Valore di ritorno

Dimensione del buffer richiesta.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metodo


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metodo


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metodo


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) metodo


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) metodo


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) metodo


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Libreria [Aspose.Slides](../../../)