---
title: ColorTranslator
second_title: Référence API Aspose.Slides pour C++
description: "Effectue des traductions de couleur. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des violations d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 66
url: /fr/system.drawing/colortranslator/
---
## ColorTranslator classe


Effectue des translations de couleur. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'operateur new, car cela entrainera des erreurs d'execution et/ou des violations d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class ColorTranslator
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Convertit la représentation de couleur HTML spécifiée en l'objet [Color](../color/) équivalent. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Convertit la couleur [Windows](../../system.windows/) spécifiée en l'objet [Color](../color/) équivalent. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Convertit l'objet [Color](../color/) spécifié en la représentation sous forme de chaîne de la couleur HTML équivalente. |
## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)