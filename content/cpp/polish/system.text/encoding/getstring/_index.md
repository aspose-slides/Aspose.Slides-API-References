---
title: GetString()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dekoduje bufor bajtów do łańcucha znaków.
type: docs
weight: 313
url: /pl/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| byte_count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) do odczytu bajtów. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(ArrayPtr\<uint8_t\>) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) do odczytu bajtów. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) do odczytu bajtów. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| index | int | Offset bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| index | int | Offset bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) metoda

Dekoduje bufor bajtów do łańcucha znaków.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) do odczytu bajtów. |
| index | int | Offset bufora wejściowego. |
| count | int | Rozmiar bufora wejściowego. |

### Wartość zwracana

[String](../../../system/string/) zdekodowanych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [Encoding](../)
* Klasa [ReadOnlySpan](../../../system/readonlyspan/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)