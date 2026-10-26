---
title: GetByteCount()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.
type: docs
weight: 235
url: /it/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metodo

Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer di caratteri. |
| index | int | Inizio della slice. |
| count | int | Dimensione della slice. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metodo

Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer di caratteri. |
| index | int | Inizio della slice. |
| count | int | Dimensione della slice. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metodo

Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer di caratteri. |
| index | int | Inizio della slice. |
| count | int | Dimensione della slice. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Encoding::GetByteCount(const String\&) metodo

Ottiene il numero di caratteri necessari per codificare una stringa.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) da codificare. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metodo

Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer di caratteri. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Encoding::GetByteCount(const char_t *, int) metodo

Ottiene il numero di caratteri necessari per codificare un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Buffer di caratteri. |
| count | int | [Buffer](../../../system/buffer/) dimensione. |

### Valore di ritorno

Dimensione del buffer richiesta.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoding](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)