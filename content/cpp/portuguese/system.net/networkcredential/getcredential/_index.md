---
title: GetCredential()
second_title: Referência da API Aspose.Slides para C++
description: Retorna credenciais para o URI especificado e o tipo de autenticação.
type: docs
weight: 92
url: /pt/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) método

Retorna credenciais para o URI especificado e o tipo de autenticação.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI. |
| authenticationType | [String](../../../system/string/) | O tipo de autenticação. |

## NetworkCredential::GetCredential(String, int32_t, String) método

Retorna credenciais para o nome do host, a porta e o tipo de autenticação especificados.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome do host. |
| port | **int32_t** | O número da porta. |
| authenticationType | [String](../../../system/string/) | O tipo de autenticação. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)