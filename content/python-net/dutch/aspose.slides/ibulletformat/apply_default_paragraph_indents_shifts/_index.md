---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Stelt de standaard niet-nul verschuivingen in voor de effectieve paragraaf Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet als je alinea-bullets/nummering inschakelt). Als bullets zijn uitgeschakeld, worden de paragraaf Indent en MarginLeft gewoon gereset (zoals PowerPoint doet als je alinea-bullets/nummering uitschakelt). Indent-verschuivingen worden toegepast met betrekking tot de huidige bullet-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul indent-verschuivingen worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (zodat de resulterende waarden lokale waarden worden).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Het aanroepen van deze methode heeft geen zin en werpt **System.InvalidOperationException** in de volgende gevallen:<br/>            als het bovenliggende geformatteerde object geen alinea is (bijvoorbeeld het aanroepen van ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() zal een uitzondering veroorzaken);<br/>            of als de alinea niet is toegevoegd aan een ITextFrame.Paragraphs-collectie (voeg deze eerst toe); |

### Zie ook
* klasse [`IBulletFormat`](/slides/python-net/nl/aspose.slides/ibulletformat)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)