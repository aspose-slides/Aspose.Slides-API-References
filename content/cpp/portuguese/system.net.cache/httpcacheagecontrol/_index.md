---
title: HttpCacheAgeControl
second_title: Referência da API Aspose.Slides para C++
description: CacheAgeControl é usado para especificar preferências em relação à idade e frescor de itens em cache.
type: docs
weight: 53
url: /pt/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl é usado para especificar preferências com relação à idade e frescor de itens em cache.

```cpp
enum class HttpCacheAgeControl
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Somente para uso interno. |
| MinFresh | 1 | O conteúdo pode ser obtido do cache se o tempo restante antes da expiração for maior ou igual ao tempo especificado com este valor. |
| MaxAge | 2 | O conteúdo pode ser obtido do cache até que fique mais antigo que a idade especificada com este valor. |
| MaxStale | 4 | O conteúdo pode ser obtido do cache após a expiração até que o tempo especificado com este valor se esgote. |
| MaxAgeAndMinFresh | 3 | MaxAge e MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge e MaxStale. |

## Veja Também

* Espaço de nomes [System::Net::Cache](../)
* Biblioteca [Aspose.Slides](../../)