---
title: GetValueOf()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor encapsulado da constante enum com o nome especificado.
type: docs
weight: 53
url: /pt/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method


Retorna o valor encapsulado da constante enum com o nome especificado.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | O nome da constante enum |
| ignoreCase | **bool** | Especifica se a distinção entre maiúsculas e minúsculas deve ser ignorada ao interpretar o nome da constante enum |

### Valor de Retorno

Um valor encapsulado da constante enum cujo nome é especificado em **str**.

## EnumValues::GetValueOf(long) const method


Retorna o valor encapsulado da constante enum com o valor especificado.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| val | long | O valor da constante enum |

### Valor de Retorno

Um valor encapsulado da constante enum cujo valor é especificado em **str**.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [String](../../string/)
* Classe [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)