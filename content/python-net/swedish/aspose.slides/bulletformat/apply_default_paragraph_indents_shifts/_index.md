---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Ställer in standard icke-nollförskjutningar för effektiv paragraph Indent och MarginLeft när bullets är aktiverade (som PowerPoint gör om man aktiverar paragraph-punkter/numrering i den). Om bullets är inaktiverade återställs bara paragraph Indent och MarginLeft (som PowerPoint gör om man inaktiverar paragraph-punkter/numrering i den). Indent-förskjutningar tillämpas med avseende på aktuell bullet-kontext – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll Indent-förskjutningar tillämpas på effektiv Indent och MarginLeft för den aktuella paragrafen (gör resultatvärdena till lokala värden).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Att anropa den här metoden spelar ingen roll och kastar **System.InvalidOperationException** i följande fall:<br/>            om föräldra-formatobjektet inte är ett paragraph (till exempel om man anropar ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() kommer ett undantag att kastas);<br/>            eller om paragraph inte har lagts till i någon ITextFrame.Paragraphs-samling (lägg till den först); |

### Se också
* klass [`BulletFormat`](/slides/python-net/sv/aspose.slides/bulletformat)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)