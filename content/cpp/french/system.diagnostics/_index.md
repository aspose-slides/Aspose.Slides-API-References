---
title: "System::Diagnostics"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 469
url: /fr/system.diagnostics/
---
## Classes

| Classe | Description |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Fournit des informations sur la version du fichier. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [PerformanceCounter](./performancecounter/) | Classe factice pour permettre la compilation du code traduit utilisant PerformanceCounter. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [Process](./process/) | Encapsule les informations et la manipulation de processus. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [ProcessStartInfo](./processstartinfo/) | Décrit les paramètres de démarrage du processus. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [StackFrame](./stackframe/) | Obtient des informations sur une seule trame de pile. MSVS uniquement. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [StackTrace](./stacktrace/) | Collection de trames de pile. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [Stopwatch](./stopwatch/) | Permet la mesure du temps. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [TraceListener](./tracelistener/) | Interface pour réagir aux informations de débogage et de trace. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |

## Structures

| Structure | Description |
| --- | --- |
| [Debug](./debug/) | Collection de méthodes de débogage permettant d'envoyer des informations de débogage aux auditeurs enregistrés. Toutes les fonctions de sortie fonctionnent uniquement dans [Debug](./debug/). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit. |
| [Debugger](./debugger/) | [Debugger](./debugger/) interface. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit. |
| [Trace](./trace/) | Fournit une interface pour accéder à la trace du débogueur (le cas échéant). Fonctionne uniquement en mode [Debug](./debug/). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit. |

## Énumérations

| Énumération | Description |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Style de la fenêtre du processus. |
| [TraceEventType](./traceeventtype/) | Identifie le type d'événement qui a déclenché la trace. |
| [TraceLevel](./tracelevel/) | Spécifie quels messages afficher pour les classes [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) et System.Diagnostics.TraceSwitch. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Type pointeur. |