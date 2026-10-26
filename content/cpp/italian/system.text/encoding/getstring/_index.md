---
title: GetString()
second_title: Riferimento API di Aspose.Slides per C++
description: Decodifica un buffer di byte in una stringa.
type: docs
weight: 313
url: /it/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metodo

Decodifica un buffer di byte in una stringa.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) da cui leggere i byte. |
| byte_count | int | Dimensione del buffer di input. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metodo

Decodifica un buffer di byte in una stringa.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) da cui leggere i byte. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metodo

Decodifica un buffer di byte in una stringa.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) da cui leggere i byte. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metodo

Decodifica un buffer di byte in una stringa.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) da cui leggere i byte. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metodo

Decodifica un buffer di byte in una stringa.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) da cui leggere i byte. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metodo

Decodifica un buffer di byte in una stringa.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) da cui leggere i byte. |
| index | int | Offset del buffer di input. |
| count | int | Dimensione del buffer di input. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metodo

Decodifica un buffer di byte in una stringa.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) da cui leggere i byte. |
| index | int | Offset del buffer di input. |
| count | int | Dimensione del buffer di input. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metodo

Decodifica un buffer di byte in una stringa.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) da cui leggere i byte. |
| index | int | Offset del buffer di input. |
| count | int | Dimensione del buffer di input. |

### Valore di ritorno

[String](../../../system/string/) di caratteri decodificati.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Encoding](../)
* Classe [ReadOnlySpan](../../../system/readonlyspan/)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)