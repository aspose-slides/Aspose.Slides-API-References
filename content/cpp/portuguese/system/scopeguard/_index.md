---
title: ScopeGuard
second_title: Referência da API Aspose.Slides para C++
description: A classe de serviço que fornece serviços para executar um determinado objeto de função quando uma instância da classe sai do escopo.
type: docs
weight: 1886
url: /pt/system/scopeguard/
---
## ScopeGuard struct

A classe de serviço que fornece serviços para executar um determinado objeto de função quando uma instância da classe sai do escopo.

```cpp
template<typename F>class ScopeGuard
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| F | O tipo do objeto de função invocado pelas instâncias da classe ScopedGuard. |

## Métodos

| Método | Descrição |
| --- | --- |
| void [Disable](./disable/)() | Desativa a invocação da guarda. |
| [ScopeGuard](./scopeguard/)(F) | Constrói uma instância configurada para invocar o objeto de função especificado. |
| [~ScopeGuard](./~scopeguard/)() | Invoca o objeto de função passado ao construtor. |

## Veja também

* Namespace [System](../)
* Library [Aspose.Slides](../../)