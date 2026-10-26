---
title: ToType()
second_title: Aspose.Slides per C++ Riferimento API
description: "Converte il valore di questa istanza in un System::Object del System::Type specificato che ha un valore equivalente, utilizzando le informazioni di formattazione specifiche della cultura specificata."
type: docs
weight: 209
url: /it/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metodo

Converte il valore di questa istanza in un [System::Object](../../object/) del tipo System::Type specificato che ha un valore equivalente, utilizzando le informazioni di formattazione specifiche della cultura fornite.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Il System::Type a cui viene convertito il valore di questa istanza. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Un'implementazione dell'interfaccia [System::IFormatProvider](../../iformatprovider/) che fornisce informazioni di formattazione specifiche della cultura. |

### Valore di ritorno

Un'istanza [System::Object](../../object/) di tipo conversionType il cui valore è equivalente al valore di questa istanza.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [IConvertible](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)