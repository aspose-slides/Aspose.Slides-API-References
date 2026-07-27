---
title: Convert()
second_title: Aspose.Slides para Referência de API C++
description: Informação RTTI.
type: docs
weight: 1
url: /pt/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) método


Informação RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto a ser convertido. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | O [System::TypeInfo](../../../system/typeinfo/) no qual o valor será convertido. |

### Valor de Retorno

O valor convertido.
## Observações


Converte um valor para o [System::TypeInfo](../../../system/typeinfo/) fornecido. 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) método


Converte um valor para o [System::TypeCode](../../../system/typecode/) fornecido.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto a ser convertido. |
| typeCode | [TypeCode](../../../system/typecode/) | O [System::TypeCode](../../../system/typecode/) no qual o valor será convertido. |

### Valor de Retorno

O valor convertido.

## Ver Também

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)