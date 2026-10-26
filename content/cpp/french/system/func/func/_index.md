---
title: Func()
second_title: Référence API Aspose.Slides pour C++
description: Constructeur par défaut qui crée null-Func.
type: docs
weight: 1
url: /fr/system/func/func/
---
## Func::Func() constructeur

Constructeur par défaut qui crée null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) constructeur

Constructeur qui crée un objet [Func](../) et attribue une valeur (soit le rappel réel ou nullptr) à celui-ci.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'argument. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arg | T\&& | Argument. |

## Func::Func(const Func\&) constructeur

Constructeur de copie.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) pour copier les données depuis. |

## Func::Func(Func\&&) constructeur

Constructeur de déplacement.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) pour déplacer les données depuis. |

## Voir aussi

* Classe [Func](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)