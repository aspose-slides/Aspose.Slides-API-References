---
title: ToType()
second_title: Referência da API Aspose.Slides para C++
description: "Converte o valor desta instância para um System::Object do System::Type especificado que possui um valor equivalente, usando as informações de formatação específicas da cultura especificada."
type: docs
weight: 209
url: /pt/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) método


Converte o valor desta instância para um [System::Object](../../object/) do System::Type especificado que possui um valor equivalente, usando as informações de formatação específicas da cultura especificada.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | O System::Type para o qual o valor desta instância é convertido. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Uma implementação de interface [System::IFormatProvider](../../iformatprovider/) que fornece informações de formatação específicas da cultura. |

### Valor de Retorno

Uma instância [System::Object](../../object/) do tipo conversionType cujo valor é equivalente ao valor desta instância.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [IConvertible](../)
* namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)