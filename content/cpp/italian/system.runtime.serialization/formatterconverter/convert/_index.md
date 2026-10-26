---
title: Convert()
second_title: Riferimento API di Aspose.Slides per C++
description: "Converte un valore nel System::TypeInfo specificato."
type: docs
weight: 1
url: /it/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metodo

Converte un valore nel [System::TypeInfo](../../../system/typeinfo/) specificato.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'oggetto da convertire. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Il [System::TypeInfo](../../../system/typeinfo/) nel quale il valore deve essere convertito. |

### Valore di ritorno

Il valore convertito.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metodo

Converte un valore nel [System::TypeCode](../../../system/typecode/) specificato.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'oggetto da convertire. |
| typeCode | [TypeCode](../../../system/typecode/) | Il [System::TypeCode](../../../system/typecode/) nel quale il valore deve essere convertito. |

### Valore di ritorno

Il valore convertito.

## Vedi anche

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [FormatterConverter](../)
* Spazio dei nomi [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)