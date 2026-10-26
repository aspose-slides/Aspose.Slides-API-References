---
title: TryParse()
second_title: Referência de API Aspose.Slides para C++
description: Tenta converter a string especificada em constante enum equivalente.
type: docs
weight: 79
url: /pt/system/enum/tryparse/
---
## Enum::TryParse(const String&, E&) método

Tenta converter a string especificada em constante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) que é interpretado como contendo o nome da constante enum |
| result | E\& | O parâmetro de saída que, se a conversão for bem-sucedida, contém o resultado da conversão na função |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false

## Enum::TryParse(const String&, bool, E&) método

Tenta converter a string especificada em constante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) que é interpretado como contendo o nome da constante enum |
| ignoreCase | **bool** | Especifica se a diferenciação de maiúsculas e minúsculas deve ser ignorada ao interpretar a string |
| result | E\& | O parâmetro de saída que, se a conversão for bem-sucedida, contém o resultado da conversão no retorno da função |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false

## Veja Também

* Classe [String](../../string/)
* Estrutura [Enum](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)