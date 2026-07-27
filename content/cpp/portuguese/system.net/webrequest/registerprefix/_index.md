---
title: RegisterPrefix()
second_title: Referência da API Aspose.Slides para C++
description: Registra o descendente WebRequest para o URI especificado.
type: docs
weight: 92
url: /pt/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) method

Registra o descendente [WebRequest](../) para o URI especificado.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The URI or the URI prefix. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Creates new instances of the [WebRequest](../) class. |

### Valor de Retorno

Verdadeiro quando o descendente [WebRequest](../) é registrado com sucesso para o URI especificado, caso contrário falso.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IWebRequestCreate](../../iwebrequestcreate/)
* Classe [WebRequest](../)
* Espaço de nomes [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)