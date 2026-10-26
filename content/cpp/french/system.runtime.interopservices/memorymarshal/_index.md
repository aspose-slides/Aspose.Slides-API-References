---
title: MemoryMarshal
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit une implémentation du marshalling mémoire. Pour la compatibilité avec le code traduit uniquement, aucun code géré n'étant pris en charge du côté C++. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 27
url: /fr/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal classe

Fournit une implémentation du marshalling mémoire. Pour la compatibilité avec le code traduit uniquement, aucun code géré n'étant pris en charge du côté C++. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class MemoryMarshal
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Convertit un [Span](../../system/span/) d'un type primitif T en [Span](../../system/span/) d'octets. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Convertit un [Span](../../system/span/) d'un type primitif TFrom en un autre type primitif TTo. |
## Voir aussi

* Espace de noms [System::Runtime::InteropServices](../)
* Bibliothèque [Aspose.Slides](../../)