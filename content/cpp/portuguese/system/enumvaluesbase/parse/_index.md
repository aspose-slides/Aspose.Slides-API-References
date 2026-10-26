---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto que representa um valor de constante de enumeração do tipo de enumeração especificado com o nome especificado.
type: docs
weight: 27
url: /pt/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) method

Retorna um objeto que representa um valor de constante de enumeração do tipo de enumeração especificado com o nome especificado.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | O objeto [TypeInfo](../../typeinfo/) que representa o tipo do valor de enumeração a ser retornado |
| str | const [String](../../string/)\& | O nome da constante enum |
| ignoreCase | **bool** | Especifica se a diferenciação entre maiúsculas e minúsculas deve ser ignorada ao interpretar o nome da constante enum |

### Valor de Retorno

Um objeto que representa o valor da constante enum cujo nome está especificado em **str**.

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [EnumValuesBase](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)