---
title: ToString()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí všechny hodnoty zadaného pole bajtů na jejich šestnáctkovou řetězcovou reprezentaci. Velikost písmen používaných v šestnáctkové notaci a oddělovač vložený mezi každý pár sousedních bajtů jsou určeny příslušnými argumenty.
type: docs
weight: 157
url: /cs/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) metoda


Převádí všechny hodnoty zadaného pole bajtů na jejich šestnáctkovou řetězcovou reprezentaci. Velikost písmen, která se použijí v šestnáctkové notaci, a oddělovač vložený mezi každým párem sousedních bajtů jsou určeny příslušnými argumenty.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) obsahující bajty k převodu |
| uppercase | **bool** | Určuje velikost písmen, která se použijí ve výsledné šestnáctkové reprezentaci |
| separator | const [String](../../string/)\& | Řetězec použitý jako oddělovač vložený mezi každým párem sousedních bajtů ve výsledném řetězci |

### Návratová hodnota

[String](../../string/) obsahující šestnáctkovou reprezentaci zadaného pole bajtů

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) metoda


Převádí hodnoty zadaného pole bajtů do jejich šestnáctkové řetězcové reprezentace počínaje zadaným indexem.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) obsahující bajty k převodu |
| startIndex | int | [Index](../../index/) v zadaném poli, od kterého se má začít převádět |

### Návratová hodnota

[String](../../string/) obsahující šestnáctkovou reprezentaci zadaného rozsahu prvků zadaného pole

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) metoda


Převádí rozsah hodnot zadaného pole bajtů do jejich šestnáctkové řetězcové reprezentace.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) obsahující bajty k převodu |
| startIndex | int | [Index](../../index/) v zadaném poli, kde začíná rozsah prvků pole bajtů, které se mají převést |
| length | int | Délka rozsahu prvků pole bajtů, které se mají převést |

### Návratová hodnota

[String](../../string/) obsahující šestnáctkovou reprezentaci zadaného rozsahu prvků zadaného pole

## Viz také

* Definice typu [ArrayPtr](../../arrayptr/)
* Třída [String](../../string/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)