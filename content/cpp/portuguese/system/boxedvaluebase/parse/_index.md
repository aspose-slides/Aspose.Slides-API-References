---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Encapsula o valor da constante de enumeração da enumeração especificada com o nome especificado. Um parâmetro especifica se a diferenciação de maiúsculas e minúsculas deve ser ignorada ao interpretar a cadeia que especifica o nome da constante de enumeração.
type: docs
weight: 53
url: /pt/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) método

Encapsula o valor da constante de enumeração da enumeração especificada com o nome especificado. Um parâmetro especifica se a diferenciação de maiúsculas e minúsculas deve ser ignorada ao interpretar a cadeia que especifica o nome da constante de enumeração.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Especifica o tipo da enumeração |
| str | const [String](../../string/)\& | O nome da constante de enumeração, cujo valor será encapsulado |
| ignoreCase | **bool** | Especifica se a diferenciação de maiúsculas e minúsculas deve ser ignorada ao interpretar a cadeia que representa o nome da constante de enumeração |

### Valor de Retorno

Um ponteiro compartilhado para o objeto que representa o valor encapsulado da constante de enumeração especificada

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) método

Encapsula o valor da constante de enumeração da enumeração especificada com o nome especificado.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Especifica o tipo da enumeração |
| str | const [String](../../string/)\& | O nome da constante de enumeração, cujo valor será encapsulado |

### Valor de Retorno

Um ponteiro compartilhado para o objeto que representa o valor encapsulado da constante de enumeração especificada

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [BoxedValueBase](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)