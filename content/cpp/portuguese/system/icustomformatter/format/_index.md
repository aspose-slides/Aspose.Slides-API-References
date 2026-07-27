---
title: Format()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma representação em string de um valor representado pelo objeto atual usando o formato especificado.
type: docs
weight: 1
url: /pt/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) método


Retorna uma representação em string de um valor representado pelo objeto atual usando o formato especificado.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | [System::String](../../string/) | O formato de string |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | O objeto a ser formatado |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | O objeto que fornece as informações de formatação |

### Valor de Retorno

A representação em string de **arg** formatada de acordo com o formato especificado por **format** e **formatProvider**

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Object](../../object/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [ICustomFormatter](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)