---
title: Convert()
second_title: Aspose.Slides para C++ Referência da API
description: "Converte um valor para o System::TypeInfo especificado."
type: docs
weight: 1
url: /pt/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) método

Converte um valor para o [System::TypeInfo](../../../system/typeinfo/) especificado.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto a ser convertido. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | O [System::TypeInfo](../../../system/typeinfo/) para o qual o valor deve ser convertido. |

### Valor de Retorno

O valor convertido.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) método

Converte um valor para o [System::TypeCode](../../../system/typecode/) especificado.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto a ser convertido. |
| typeCode | [TypeCode](../../../system/typecode/) | O [System::TypeCode](../../../system/typecode/) para o qual o valor deve ser convertido. |

### Valor de Retorno

O valor convertido.

## Veja Também

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [FormatterConverter](../)
* Espaço de nomes [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)