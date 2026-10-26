---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Setzt standardmäßige Nicht-Null-Verschiebungen für den effektiven Absatz-Indent und MarginLeft, wenn Aufzählungszeichen aktiviert sind (wie PowerPoint dies tut, wenn Absatz-Aufzählungszeichen/Nummerierung aktiviert werden). Wenn Aufzählungszeichen deaktiviert sind, wird lediglich der Absatz-Indent und MarginLeft zurückgesetzt (wie PowerPoint dies tut, wenn Absatz-Aufzählungszeichen/Nummerierung deaktiviert werden). Indent-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts – angewendet. Nicht-Null-Indent-Verschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (damit die Ergebniswerte lokale Werte sind).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Der Aufruf dieser Methode ist irrelevant und wirft **System.InvalidOperationException** in den folgenden Fällen:<br/>            wenn das übergeordnete formatierte Objekt kein Absatz ist (zum Beispiel Aufruf von ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() wirft eine Ausnahme);<br/>            oder wenn der Absatz zu keiner ITextFrame.Paragraphs-Sammlung hinzugefügt wurde (zuerst hinzufügen); |



### Siehe auch
* Klasse [`IBulletFormat`](/slides/python-net/de/aspose.slides/ibulletformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)