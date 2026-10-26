---
title: what()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Implémente la méthode what() qui est appelée par la classe ExceptionWrapper. Malgré le fait que cette classe n'hérite pas de std::exception, les classes dérivées peuvent utiliser les membres protégés/privés pour implémenter leur logique. Déplacer l'implémentation de cette méthode vers ExceptionWrapper peut casser cette logique."
type: docs
weight: 105
url: /fr/system/details_exception/what/
---
## Details_Exception::what() const méthode

Implémente la méthode [what()](./) qui est appelée par la classe [ExceptionWrapper](../../exceptionwrapper/). Bien que cette classe ne soit pas dérivée de std::exception, les classes dérivées peuvent utiliser les membres protected/private pour implémenter leur logique. Déplacer l'implémentation de cette méthode vers le [ExceptionWrapper](../../exceptionwrapper/) peut casser cette logique.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Valeur de retour

La description de l'exception.

## Voir aussi

* Classe [Details_Exception](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)