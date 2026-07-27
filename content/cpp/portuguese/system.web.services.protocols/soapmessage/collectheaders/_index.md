---
title: CollectHeaders()
second_title: Referência da API Aspose.Slides para C++
description: Define a coleção interna dos cabeçalhos SOAP.
type: docs
weight: 326
url: /pt/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) method


Define a coleção interna dos cabeçalhos SOAP.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O objeto de onde obter os cabeçalhos SOAP. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | Uma coleção de cabeçalhos a partir da qual a coleção interna será preenchida. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | A direção do cabeçalho SOAP. |

## Veja Também

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [SoapMessage](../)
* Espaço de nomes [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)