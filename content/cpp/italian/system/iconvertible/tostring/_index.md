---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: "Converte il valore di questa istanza in un System::String equivalente utilizzando le informazioni di formattazione specifiche per la cultura specificata."
type: docs
weight: 196
url: /it/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) metodo


Converte il valore di questa istanza in un [System::String](../../string/) equivalente utilizzando le informazioni di formattazione specifiche per la cultura specificata.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Un'implementazione dell'interfaccia [System::IFormatProvider](../../iformatprovider/) che fornisce informazioni di formattazione specifiche per la cultura. |

### Valore di ritorno

Un'istanza [System::String](../../string/) equivalente al valore di questa istanza.

## IConvertible::ToString() const metodo


Analogo del metodo [Object.ToString()](../../object/tostring/) di C#. Consente la conversione di oggetti personalizzati in stringa.

```cpp
virtual String System::Object::ToString() const
```


### Valore di ritorno

Rappresentazione [String](../../string/) fornita dalla classe finale.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [IConvertible](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)