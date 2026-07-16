---
title: FileVersionInfo
second_title: Référence API Aspose.Slides pour C++
description: "Fournit des informations sur la version du fichier. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 1
url: /fr/system.diagnostics/fileversioninfo/
---
## FileVersionInfo classe

Fournit des informations sur la version du fichier. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class FileVersionInfo
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Obtient le champ de version du produit. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Obtient les informations de version du fichier ; non implémenté. |
## Voir aussi

* Espace de noms [System::Diagnostics](../)
* Bibliothèque [Aspose.Slides](../../)