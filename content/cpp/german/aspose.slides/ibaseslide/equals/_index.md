---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datum Platzhalter.
type: docs
weight: 183
url: /de/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) Methode

Bestimmt, ob die beiden [IBaseSlide](../)-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Identifier-Werte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Das [IBaseSlide](../) zum Vergleich mit dem aktuellen [IBaseSlide](../). |

### Rückgabewert

**true** if the specified [IBaseSlide](../) is equal to the current [IBaseSlide](../); otherwise, **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)