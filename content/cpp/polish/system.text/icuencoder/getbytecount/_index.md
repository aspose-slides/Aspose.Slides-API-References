---
title: GetByteCount()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zwraca liczbę bajtów potrzebnych do zakodowania bufora.
type: docs
weight: 40
url: /pl/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metoda

Zwraca liczbę bajtów potrzebnych do zakodowania bufora.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| index | int | [Buffer](../../../system/buffer/) przesunięcie. |
| count | int | Liczba znaków do zakodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |

### Wartość zwracana

Liczba bajtów wymagana do zakodowania bufora.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metoda

Zwraca liczbę bajtów potrzebnych do zakodowania bufora.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| count | int | Liczba znaków do zakodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |

### Wartość zwracana

Liczba bajtów wymagana do zakodowania bufora.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUEncoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)