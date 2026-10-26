---
title: ToBase64String()
second_title: Aspose.Slides pro C++ API Reference
description: Base-64 kóduje prvky ve specifikovaném poli bajtů a vrací zakódovaná data jako řetězec.
type: docs
weight: 40
url: /cs/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metoda

Base-64 kóduje prvky ve specifikovaném poli bajtů a vrací zakódovaná data jako řetězec.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů k zakódování |
| insert_line_breaks | **bool** | Určuje, zda mají být po každých 76 znacích base-64 vloženy znaky konce řádku |

### Návratová hodnota

Řetězec obsahující base-64 zakódovanou reprezentaci vstupního pole

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metoda

Base-64 kóduje rozsah prvků ve specifikovaném poli bajtů a vrací zakódovaná data jako řetězec.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující rozsah prvků k zakódování |
| offset_in | int | Index prvku ve vstupním poli, od kterého začíná rozsah k zakódování |
| length | int | Délka rozsahu prvků k zakódování |
| insert_line_breaks | **bool** | Určuje, zda mají být po každých 76 znacích base-64 vloženy znaky konce řádku |

### Návratová hodnota

Řetězec obsahující base-64 zakódovanou reprezentaci rozsahu prvků vstupního pole

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metoda

Base-64 kóduje prvky ve specifikovaném poli bajtů a vrací zakódovaná data jako řetězec.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů k zakódování |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Určuje formátovací možnosti base-64 zakódovaných dat |

### Návratová hodnota

Řetězec obsahující base-64 zakódovanou reprezentaci vstupního pole

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metoda

Base-64 kóduje rozsah prvků ve specifikovaném poli bajtů a vrací zakódovaná data jako řetězec.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující rozsah prvků k zakódování |
| offset_in | int | Index prvku ve vstupním poli, od kterého začíná rozsah k zakódování |
| length | int | Délka rozsahu prvků k zakódování |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Určuje formátovací možnosti base-64 zakódovaných dat |

### Návratová hodnota

Řetězec obsahující base-64 zakódovanou reprezentaci rozsahu prvků vstupního pole

## Viz také

* Výčet [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../../string/)
* Struktura [Convert](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)