---
title: DoTryFinally()
second_title: Référence API Aspose.Slides pour C++
description: La fonction unique qui émule le comportement de l'instruction try[-catch]-finally de C#. Lors de la traduction de l'instruction try[-catch]-finally de C# avec l'option du traducteur finally_statement_as_lambda définie sur true, l'instruction est traduite en appel de cette méthode.
type: docs
weight: 2406
url: /fr/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) fonction


La fonction unique qui émule le comportement de l'instruction try[-catch]-finally de C#. Lors de la traduction de l'instruction try[-catch]-finally de C# avec l'option du traducteur finally_statement_as_lambda définie sur true, l'instruction est traduite en appel de cette méthode.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet fonction qui implémente la partie try[-catch] de l'instruction try[-catch]-finally émule |
| F | Le type de l'objet fonction qui implémente la partie finally de l'instruction try[-catch]-finally émule |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | L'objet fonction dont le corps contient l'implémentation de la partie try[-catch] de l'instruction try[-catch]-finally émule |
| finallyBlock | F\&& | L'objet fonction dont le corps contient l'implémentation de la partie finally de l'instruction try[-catch]-finally émule |

## System::DoTryFinally(T\&&, F\&&) fonction


La fonction unique qui émule le comportement de l'instruction try[-catch]-finally de C#. Lors de la traduction de l'instruction try[-catch]-finally de C# avec l'option du traducteur finally_statement_as_lambda définie sur true, l'instruction est traduite en appel de cette méthode. Cette surcharge gère le cas où la valeur de retour de l'objet fonction qui implémente la partie try[-catch] de l'instruction try[-catch]-finally est bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet fonction qui implémente la partie try[-catch] de l'instruction try[-catch]-finally émule |
| F | Le type de l'objet fonction qui implémente la partie finally de l'instruction try[-catch]-finally émule |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | L'objet fonction dont le corps contient l'implémentation de la partie try[-catch] de l'instruction try[-catch]-finally émule |
| finallyBlock | F\&& | L'objet fonction dont le corps contient l'implémentation de la partie finally de l'instruction try[-catch]-finally émule |

## System::DoTryFinally(T\&&, F\&&) fonction


La fonction unique qui émule le comportement de l'instruction try[-catch]-finally de C#. Lors de la traduction de l'instruction try[-catch]-finally de C# avec l'option du traducteur finally_statement_as_lambda définie sur true, l'instruction est traduite en appel de cette méthode. Cette surcharge gère le cas où la valeur de retour de l'objet fonction qui implémente la partie try[-catch] de l'instruction try[-catch]-finally est bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet fonction qui implémente la partie try[-catch] de l'instruction try[-catch]-finally émule |
| F | Le type de l'objet fonction qui implémente la partie finally de l'instruction try[-catch]-finally émule |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | L'objet fonction dont le corps contient l'implémentation de la partie try[-catch] de l'instruction try[-catch]-finally émule |
| finallyBlock | F\&& | L'objet fonction dont le corps contient l'implémentation de la partie finally de l'instruction try[-catch]-finally émule |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)