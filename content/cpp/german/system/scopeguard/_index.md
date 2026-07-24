---
title: ScopeGuard
second_title: Aspose.Slides für C++ API-Referenz
description: Die Dienstklasse, die Dienste zum Ausführen eines bestimmten Funktionsobjekts bereitstellt, wenn eine Instanz der Klasse aus dem Gültigkeitsbereich geht.
type: docs
weight: 1886
url: /de/system/scopeguard/
---
## ScopeGuard-Struktur


Die Dienstklasse, die Dienste zum Ausführen eines bestimmten Funktionsobjekts bereitstellt, wenn eine Instanz der Klasse aus dem Gültigkeitsbereich geht.

```cpp
template<typename F>class ScopeGuard
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| F | Der Typ des Funktionsobjekts, das von den Instanzen der ScopedGuard-Klasse aufgerufen wird. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Disable](./disable/)() | Deaktiviert den Aufruf des Guards. |
| [ScopeGuard](./scopeguard/)(F) | Konstruiert eine Instanz, die zum Aufrufen des angegebenen Funktionsobjekts eingerichtet ist. |
| [~ScopeGuard](./~scopeguard/)() | Ruft das dem Konstruktor übergebene Funktionsobjekt auf. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)