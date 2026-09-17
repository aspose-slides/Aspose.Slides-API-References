---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Legt standardmäßige, von Null verschiedene Verschiebungen für den effektiven Absatz Indent und MarginLeft fest, wenn Aufzählungszeichen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung aktiviert werden). Ist Aufzählungszeichen deaktiviert, wird lediglich der Absatz Indent und MarginLeft zurückgesetzt (wie PowerPoint es tut, wenn Absatz-Aufzählungszeichen/Nummerierung deaktiviert werden). Einrückungs-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext angewendet – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts. Von Null verschiedene Einrückungs-Verschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (damit die Ergebniswerte lokale Werte sind).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Der Aufruf dieser Methode ist egal und wirft **System.InvalidOperationException** in den folgenden Fällen:<br/>            wenn das übergeordnete formatierte Objekt kein Absatz ist (zum Beispiel ruft man ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() auf, wird eine Ausnahme ausgelöst);<br/>            oder wenn der Absatz zu keiner ITextFrame.Paragraphs-Sammlung hinzugefügt wurde (zuerst hinzufügen); |

### Siehe auch
* Klasse [`BulletFormat`](/slides/python-net/de/aspose.slides/bulletformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)