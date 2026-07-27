---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Converte todos os valores do array de bytes especificado para sua representação hexadecimal em forma de string. O caso das letras a ser usado na notação hexadecimal e o separador inserido entre cada par de bytes vizinhos são especificados pelos argumentos correspondentes.
type: docs
weight: 157
url: /pt/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) método

Converte todos os valores do array de bytes especificado para sua representação hexadecimal em forma de string. O caso das letras a ser usado na notação hexadecimal e o separador inserido entre cada par de bytes vizinhos são especificados pelos argumentos correspondentes.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a converter |
| uppercase | **bool** | Especifica o caso das letras a ser usado na representação hexadecimal resultante |
| separator | const [String](../../string/)\& | Uma string usada como separador inserida entre cada par de bytes vizinhos na string resultante |

### Valor de Retorno

[String](../../string/) contendo a representação hexadecimal do array de bytes especificado

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) método

Converte valores do array de bytes especificado para sua representação hexadecimal em forma de string a partir do índice especificado.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a converter |
| startIndex | int | [Index](../../index/) no array especificado onde iniciar a conversão |

### Valor de Retorno

[String](../../string/) contendo a representação hexadecimal do intervalo especificado de elementos do array especificado

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) método

Converte um intervalo de valores do array de bytes especificado para sua representação hexadecimal em forma de string.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) que contém bytes a converter |
| startIndex | int | [Index](../../index/) no array especificado onde começa o intervalo de elementos do array de bytes a ser convertido |
| length | int | O comprimento do intervalo dos elementos do array de bytes a converter |

### Valor de Retorno

[String](../../string/) contendo a representação hexadecimal do intervalo especificado de elementos do array especificado

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../../string/)
* Classe [BitConverter](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)