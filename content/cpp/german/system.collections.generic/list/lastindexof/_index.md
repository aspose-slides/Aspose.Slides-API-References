---
title: LastIndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Liste zurück.
type: docs
weight: 469
url: /de/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const Methode

Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Liste zurück.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Das zu suchende Objekt in der Liste |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens von item im gesamten [List](../), falls gefunden; sonst -1.

## List::LastIndexOf(const T\&, int32_t) const Methode

Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Vorkommens im Bereich der Elemente im [List](../) zurück, der vom ersten Element bis zum angegebenen Index reicht.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Das zu suchende Objekt in der Liste |
| index | **int32_t** | Der nullbasierte Startindex der Rückwärtssuche. |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens von item im Bereich der Elemente im [List](../), der vom ersten Element bis zum Index reicht, falls gefunden; sonst -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const Methode

Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Vorkommens im Bereich der Elemente im [List](../) zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | const T\& | Das zu suchende Objekt im [List](../) |
| index | **int32_t** | Der nullbasierte Startindex der Rückwärtssuche. |
| count | **int32_t** | Die Anzahl der Elemente im zu durchsuchenden Abschnitt. |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens von item im Bereich der Elemente im [List](../), der count Elemente enthält und am Index endet, falls gefunden; sonst -1.

## Siehe auch

* Klasse [List](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)