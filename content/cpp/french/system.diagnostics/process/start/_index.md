---
title: Start()
second_title: Référence de l'API Aspose.Slides pour C++
description: Démarre le processus avec des paramètres prédéfinis.
type: docs
weight: 14
url: /fr/system.diagnostics/process/start/
---
## Process::Start() méthode

Démarre le processus avec des paramètres prédéfinis.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) méthode

Démarre le processus avec le chemin et les arguments spécifiés.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) chemin. |
| arguments | const [String](../../../system/string/)\& | [Process](../) paramètres. |

### Valeur de retour

[Object](../../../system/object/) attaché au processus nouvellement démarré.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) méthode

Démarre le processus avec le chemin et les arguments spécifiés.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Information sur le processus à démarrer. |

### Valeur de retour

[Object](../../../system/object/) attaché au processus nouvellement démarré.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Process](../)
* classe [String](../../../system/string/)
* classe [ProcessStartInfo](../../processstartinfo/)
* espace de noms [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)