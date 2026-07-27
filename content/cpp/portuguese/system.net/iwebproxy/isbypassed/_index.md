---
title: IsBypassed()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um valor que indica se o proxy não deve ser usado para o host especificado.
type: docs
weight: 40
url: /pt/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) método

Retorna um valor que indica se o proxy não deve ser usado para o host especificado.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI do host a ser verificado. |

### Valor de Retorno

True quando o servidor proxy não deve ser usado, caso contrário false.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)