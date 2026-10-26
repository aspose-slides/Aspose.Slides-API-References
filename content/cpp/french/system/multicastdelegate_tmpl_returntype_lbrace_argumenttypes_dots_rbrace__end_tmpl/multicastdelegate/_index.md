---
title: MulticastDelegate()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une collection vide.
type: docs
weight: 1
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() méthode

Construit une collection vide.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) méthode

Équivalent au constructeur par défaut.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) méthode

Effectue une copie superficielle de la collection de délégués.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| o | const MulticastDelegate\& | Une instance de la classe MulticastDelegate dont la collection de délégués doit être copiée. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) méthode

Constructeur de déplacement.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| o | MulticastDelegate\&& | Une instance de la classe MulticastDelegate dont la collection de délégués doit être déplacée. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) méthode

Construit une instance et place le délégué spécifié dans la collection de délégués.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Un délégué à placer dans la collection de délégués |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) méthode

Construit une instance et place la valeur spécifiée dans la collection de délégués.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de la valeur à placer dans la collection de délégués de l'instance nouvellement construite; le type doit être convertible au type Callback. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arg | T | Une valeur à placer dans la collection de délégués |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) méthode

Construit une instance et place la valeur spécifiée dans la collection de délégués.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Une valeur à placer dans la collection de délégués |

## Voir aussi

* Typedef [Callback](../callback/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)