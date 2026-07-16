---
title: Debug
second_title: Référence de l'API Aspose.Slides pour C++
description: Collection de méthodes de débogage permettant l'envoi d'informations de débogage aux auditeurs enregistrés. Toutes les fonctions de sortie fonctionnent uniquement en mode Debug. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 105
url: /fr/system.diagnostics/debug/
---
## Debug struct

Collection de méthodes de débogage permettant l'envoi d'informations de débogage aux auditeurs enregistrés. Toutes les fonctions de sortie fonctionnent uniquement dans [Debug](./). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class Debug
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Vérifie la condition et envoie des informations en cas d'échec. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Vérifie la condition et envoie des informations en cas d'échec. |
| static void [Assert](./assert/)(**bool**, const char *) | Vérifie la condition et envoie des informations en cas d'échec. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Vérifie la condition et envoie des informations en cas d'échec. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Envoie un message d'échec. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Accède à la liste statique des auditeurs. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Imprime le message sur l'interface de débogage. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Imprime le message sur l'interface de débogage. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Écrit une chaîne sur l'interface de débogage. |
| static void [Write](./write/)(const char_t *) | Écrit une chaîne sur l'interface de débogage. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Écrit une chaîne sur l'interface de débogage si une condition est vraie. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Écrit une ligne sur l'interface de débogage. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Écrit une ligne sur l'interface de débogage. |
| static void [WriteLine](./writeline/)(const char_t *) | Écrit une ligne sur l'interface de débogage. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Écrit une ligne sur l'interface de débogage. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Écrit une ligne sur l'interface de débogage si une condition est vraie. |
## Voir aussi

* Espace de noms [System::Diagnostics](../)
* Bibliothèque [Aspose.Slides](../../)