---
title: CompareOrdinal()
second_title: Referência da API Aspose.Slides para C++
description: Compara duas strings usando o modo ordinal (menor, igual ou maior).
type: docs
weight: 833
url: /pt/system/string/compareordinal/
---
## String::CompareOrdinal(const String&, const String&) método

Compara duas strings por ordem ordinal (menor, igual ou maior).

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| strB | const [String](../)\& | Segunda string a ser comparada. |

### Valor de retorno

Valor negativo se a primeira substring for menor que a segunda, zero se forem iguais, valor positivo caso contrário.

## String::CompareOrdinal(const String&, int, const String&, int, int) método

Compara duas strings por ordem ordinal (menor, igual ou maior).

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| indexA | int | Início da substring da primeira string. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| indexB | int | Início da substring da segunda string. |
| length | int | Número de caracteres a comparar. |

### Valor de retorno

Valor negativo se a primeira substring for menor que a segunda, zero se forem iguais, valor positivo caso contrário.

## Veja também

* Classe [String](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)