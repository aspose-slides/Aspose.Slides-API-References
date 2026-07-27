---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Escreve o caractere especificado no fluxo.
type: docs
weight: 40
url: /pt/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) método

Escreve o caractere especificado no fluxo.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | O value a ser escrito |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método

Escreve o sub-intervalo especificado de caracteres do array de caracteres especificado no fluxo.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |
| index | **int32_t** | Um índice baseado em 0 do elemnet em **buffer** onde a subfaixa a ser escrita começa |
| count | **int32_t** | O número de caracteres na subfaixa a ser escrita |

## StringWriter::Write(const String\&) método

Escreve a string especificada no fluxo.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A string a ser escrita |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringWriter](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)