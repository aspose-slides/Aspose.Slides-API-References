---
title: Format()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una rappresentazione stringa di un valore rappresentato dall'oggetto corrente utilizzando il formato specificato.
type: docs
weight: 1
url: /it/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) metodo

Restituisce una rappresentazione stringa di un valore rappresentato dall'oggetto corrente utilizzando il formato specificato.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [System::String](../../string/) | Il formato stringa |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | L'oggetto da formattare |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | L'oggetto che fornisce le informazioni di formattazione |

### Valore restituito

La rappresentazione stringa di **arg** formattata secondo il formato specificato da **format** e **formatProvider**

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Object](../../object/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [ICustomFormatter](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)