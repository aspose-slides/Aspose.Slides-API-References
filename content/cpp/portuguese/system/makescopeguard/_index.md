---
title: MakeScopeGuard()
second_title: Referência da API Aspose.Slides para C++
description: Uma função fábrica que cria instâncias da classe ScopedGuard.
type: docs
weight: 2809
url: /pt/system/makescopeguard/
---
## System::MakeScopeGuard(F) função

Uma função fábrica que cria instâncias da classe ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| The | tipo do objeto de função a ser invocado pelo objeto ScopedGuard construído |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| f | F | O objeto de função a ser passado ao construtor da classe ScopedGuard. |

### Valor de retorno

Uma nova instância da classe ScopedGuard

## Ver também

* Estrutura [ScopeGuard](../scopeguard/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)