---
title: Interlocked
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit une API pour les opérations sécurisées pour les threads. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quelles que soient les circonstances.
type: docs
weight: 131
url: /fr/system.threading/interlocked/
---
## Classe Interlocked

Fournit une API pour les opérations sécurisées pour les threads. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quelles que soient les circonstances.

```cpp
class Interlocked
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Augmente la valeur de façon atomique. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Augmente la valeur de façon atomique. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-échange la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et stocke la nouvelle valeur seulement si la valeur stockée correspond à celle attendue. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Compare-échange la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et stocke la nouvelle valeur seulement si la valeur stockée correspond à celle attendue. Non implémenté. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Compare-échange la valeur d’une variable : vérifie si la variable est égale à une valeur spécifique et stocke la nouvelle valeur seulement si la valeur stockée correspond à celle attendue. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Décrémente la valeur de façon atomique. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Décrémente la valeur de façon atomique. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Échange la valeur d’une variable : stocke la nouvelle valeur et renvoie la valeur que la variable possédait immédiatement avant le stockage. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Échange la valeur d’une variable : stocke la nouvelle valeur et renvoie la valeur que la variable possédait immédiatement avant le stockage. Non implémenté. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Augmente la valeur de façon atomique via la procédure d’échange-addition. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Augmente la valeur de façon atomique via la procédure d’échange-addition. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Incrémente la valeur de façon atomique. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Incrémente la valeur de façon atomique. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Renvoie une valeur 64 bits, chargée comme une opération atomique. |

## Voir aussi

* Espace de noms [System::Threading](../)
* Bibliothèque [Aspose.Slides](../../)