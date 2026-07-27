---
title: CombineMode
second_title: Aspose.Slides para C++ Referência da API
description: Especifica como as regiões de recorte são combinadas.
type: docs
weight: 170
url: /pt/system.drawing.drawing2d/combinemode/
---
## enum CombineMode

Especifica como as regiões de recorte são combinadas.

```cpp
enum class CombineMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Replace | 0 | Uma região de recorte é substituída por outra. |
| Intersect | 1 | As duas regiões de recorte são combinadas tomando sua interseção. |
| Union | 2 | As duas regiões de recorte são combinadas tomando a união de ambas. |
| Xor | 3 | As duas regiões de recorte são combinadas tomando apenas a área delimitada por uma das regiões ou pela outra, mas não ambas. |
| Exclude | 4 | Duas regiões de recorte são combinadas tomando a área da primeira região que não intersecta com a segunda. |
| Complement | 5 | Duas regiões de recorte são combinadas tomando a área da segunda região que não intersecta com a primeira. |

## Veja Também

* Namespace [System::Drawing::Drawing2D](../)
* Biblioteca [Aspose.Slides](../../)