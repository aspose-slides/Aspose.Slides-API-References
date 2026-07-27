---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: "Converte o valor desta instância em um System::String equivalente usando as informações de formatação específicas da cultura especificada."
type: docs
weight: 196
url: /pt/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) method


Converte o valor desta instância em um [System::String](../../string/) equivalente usando as informações de formatação específicas da cultura especificada.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Uma implementação de interface [System::IFormatProvider](../../iformatprovider/) que fornece informações de formatação específicas da cultura. |

### Valor de retorno

Uma instância [System::String](../../string/) equivalente ao valor desta instância.

## IConvertible::ToString() const method


Analógica ao método [Object.ToString()](../../object/tostring/) do C#. Permite converter objetos personalizados em string.

```cpp
virtual String System::Object::ToString() const
```


### Valor de retorno

[String](../../string/) representação conforme fornecida pela classe final.

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)