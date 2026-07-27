---
title: InternalAdd()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o cookie especificado à coleção.
type: docs
weight: 118
url: /pt/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) method

Adiciona o cookie especificado à coleção.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | O cookie a ser adicionado. |
| isStrict | **bool** | Verdadeiro quando o cookie especificado deve substituir o antigo, caso contrário falso. |

### Valor de Retorno

0 quando o cookie especificado substituiu o antigo, caso contrário 1.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)