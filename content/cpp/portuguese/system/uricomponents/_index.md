---
title: UriComponents
second_title: Aspose.Slides para C++ Referência da API
description: Representa componentes de URI.
type: docs
weight: 3251
url: /pt/system/uricomponents/
---
## UriComponents enum

Representa os componentes de URI.

```cpp
enum class UriComponents
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Scheme | 1 | Os dados do Scheme. |
| UserInfo | 2 | Os dados do UserInfo. |
| Host | 4 | Os dados do Host. |
| Port | 8 | Os dados do Port. |
| SchemeAndServer | n/a | Os dados do Scheme, Host e Port. |
| Path | 16 | Os dados do LocalPath. |
| Query | 32 | Os dados do Query. |
| PathAndQuery | n/a | Os dados do LocalPath e Query. |
| HttpRequestUrl | n/a | Os dados do Scheme, Host, Port, Query e LocalPath. |
| Fragment | 64 | Os dados do Fragment. |
| AbsoluteUri | n/a | Os dados do Scheme, Host, Port, Query, LocalPath e Fragment. |
| StrongPort | 128 | Os dados do Port; se os dados da porta não estiverem presentes no [Uri](../uri/) e uma porta padrão tiver sido atribuída ao Scheme, a porta padrão é retornada; se não houver porta padrão, -1 é retornado. |
| HostAndPort | n/a | Os dados do Host e Port; se os dados da porta não estiverem presentes no [Uri](../uri/) e uma porta padrão tiver sido atribuída ao Scheme, a porta padrão é retornada; se não houver porta padrão, -1 é retornado. |
| StrongAuthority | n/a | Os dados do UserInfo, Host e Port. Se não houver dados de porta no [Uri](../uri/) e uma porta padrão tiver sido atribuída ao Scheme, a porta padrão é retornada; se não houver porta padrão, -1 é retornado. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Especifica que o delimitador deve ser incluído. |
| SerializationInfoString | n/a | O contexto completo [Uri](../uri/) que é necessário para os Serializers [Uri](../uri/). O contexto inclui o escopo IPv6. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)