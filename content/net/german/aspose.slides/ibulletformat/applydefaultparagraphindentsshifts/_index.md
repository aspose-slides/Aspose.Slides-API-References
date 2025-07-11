---
title: ApplyDefaultParagraphIndentsShifts
second_title: Aspose.Slides für .NET API-Referenz
description: Setzt standardmäßige, von null verschiedene Verschiebungen für effektive Absatz-Indentation und MarginLeft, wenn Aufzählungen aktiviert sind, wie PowerPoint es tut, wenn Aufzählungs-/Nummerierungsoptionen aktiviert sind. Wenn Aufzählungen deaktiviert sind, wird einfach die Absatz-Indentation und MarginLeft zurückgesetzt, wie PowerPoint es tut, wenn Aufzählungen/Nummerierungen deaktiviert sind. Die Einzüge werden in Bezug auf den aktuellen Aufzählungskontext - IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Teils angewendet. Verschiebungen, die von null verschieden sind, werden auf die effektiven Indentationen und MarginLeft des aktuellen Absatzes angewendet, wodurch die Ergebniswerte lokale Werte werden.
type: docs
weight: 110
url: /de/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---

## IBulletFormat.ApplyDefaultParagraphIndentsShifts-Methode

Setzt standardmäßige, von null verschiedene Verschiebungen für effektive Absatz-Indentation und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Aufzählungs-/Nummerierungsoptionen aktiviert sind). Wenn Aufzählungen deaktiviert sind, wird einfach die Absatz-Indentation und MarginLeft zurückgesetzt (wie PowerPoint es tut, wenn Aufzählungen/Nummerierungen deaktiviert sind). Die Einzüge werden in Bezug auf den aktuellen Aufzählungskontext - IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Teils angewendet. Verschiebungen, die von null verschieden sind, werden auf die effektiven Indentationen und MarginLeft des aktuellen Absatzes angewendet (damit die Ergebniswerte lokale Werte werden).

```csharp
public void ApplyDefaultParagraphIndentsShifts()
```

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Das Aufrufen dieser Methode ist irrelevant und wirft eine InvalidOperationException in folgenden Fällen: wenn das übergeordnete formatierte Objekt kein Absatz ist (zum Beispiel wird das Aufrufen von ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() eine Ausnahme auslösen); oder wenn der Absatz nicht zu einer ITextFrame.Paragraphs-Sammlung hinzugefügt wurde (füge ihn zuerst hinzu); |

### Siehe auch

* Schnittstelle [IBulletFormat](../../ibulletformat)
* Namespace [Aspose.Slides](../../ibulletformat)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->