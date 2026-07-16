---
title: SafeInvoke()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémentation de la traduction de l'opérateur '?.'.
type: docs
weight: 2614
url: /fr/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) fonction

Implémentation de la traduction de l'opérateur '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T0 | type d'expression. |
| T1 | Type du lambda encapsulant l'expression 'WhenTrue'. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| expr | T0\&& | valeur d'expression. |
| func | T1\&& | expression 'WhenTrue' liée au foncteur. |

### Valeur de retour

Si la valeur de expr n'est pas nulle, renvoie func appelé avec sa valeur comme premier argument, sinon renvoie null.

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)