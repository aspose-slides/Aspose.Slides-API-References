---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Sätter standardvärden för icke-noll förskjutningar för effektiv paragraf-Indent och MarginLeft när bullets är aktiverade (likt PowerPoint gör om du aktiverar paragraf-bullets/numrering). Om bullets är inaktiverade återställs bara paragraf-Indent och MarginLeft (likt PowerPoint gör om du inaktiverar paragraf-bullets/numrering). Indent-förskjutningar tillämpas med avseende på det aktuella bullet-kontextet - IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll Indent-förskjutningar tillämpas på effektiv Indent och MarginLeft för den aktuella paragrafen (gör resultatinvärdena till lokala värden).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Att anropa den här metoden spelar ingen roll och kastar **System.InvalidOperationException** i följande fall:<br/>            om föräldraformaterat objekt inte är ett stycke (till exempel att anropa ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() kommer kasta ett undantag);<br/>            eller om stycket inte har lagts till i någon ITextFrame.Paragraphs-samling (lägg till det först); |



### Se även
* klass [`IBulletFormat`](/slides/python-net/sv/aspose.slides/ibulletformat)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)