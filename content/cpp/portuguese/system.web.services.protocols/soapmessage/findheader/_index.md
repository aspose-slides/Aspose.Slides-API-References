---
title: FindHeader()
second_title: Referência da API Aspose.Slides para C++
description: Encontre o mapeamento de cabeçalho pelo tipo de cabeçalho especificado.
type: docs
weight: 352
url: /pt/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) método


Encontre o mapeamento de cabeçalho pelo tipo de cabeçalho especificado.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | A coleção dos mapeamentos de cabeçalho. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de cabeçalho a ser procurado. |

### Valor de Retorno

O mapeamento de cabeçalho.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)