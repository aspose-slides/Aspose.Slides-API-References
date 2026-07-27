---
title: RegexOptions
second_title: Referência da API Aspose.Slides para C++
description: Opções de regex.
type: docs
weight: 118
url: /pt/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum

[Regex](../regex/) opções.

```cpp
enum class RegexOptions
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Comportamento padrão. |
| Compiled | 1 | Compila regex para desempenho. Sempre feito por padrão. |
| CultureInvariant | 2 | Usa correspondência invariável à cultura. Ignorado. |
| ECMAScript | 4 | Usa sintaxe ECMAScript. Ignorado. |
| ExplicitCapture | 8 | Apenas captura explícita. Ignorado. |
| IgnoreCase | 16 | Ignora maiúsculas e minúsculas ao combinar. |
| IgnorePatternWhitespace | 32 | Ignora espaços em branco no padrão. Não suportado. |
| Multiline | 64 | Trata '^' e '$' como início e fim da linha, não da string inteira. |
| RightToLeft | 128 | Correspondência da direita para a esquerda. Não suportado. |
| Singleline | 256 | Faz com que '.' corresponda a qualquer caractere sem exceções (normalmente, caracteres de quebra de linha não são correspondidos). |

## Veja Também

* Namespace [System::Text::RegularExpressions](../)
* Biblioteca [Aspose.Slides](../../)