---
title: ToObject()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor inteiro sem sinal de 64 bits especificado em um membro de enumeração.
type: docs
weight: 40
url: /pt/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) método


Converte o valor inteiro sem sinal de 64 bits especificado em um membro de enumeração.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | O tipo de enumeração a ser retornado. |
| value | **uint64_t** | O valor a ser convertido em um membro de enumeração. |

### Valor de Retorno

Uma instância da enumeração definida como valor.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) método


Converte o objeto especificado com um valor inteiro em um membro de enumeração.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | O tipo de enumeração a ser retornado. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | O valor a ser convertido em um membro de enumeração. |

### Valor de Retorno

Um objeto de enumeração cujo valor é valor.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* classe [Object](../../object/)
* classe [TypeInfo](../../typeinfo/)
* classe [EnumValuesBase](../)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)