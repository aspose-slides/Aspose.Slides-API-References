---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Nastaví výchozí nenulové posuny pro efektivní odstavec Indent a MarginLeft, pokud jsou zapnuté odrážky (tak, jak PowerPoint dělá, když povolíte odrážky/číslování odstavců). Pokud jsou odrážky vypnuté, jednoduše resetuje odstavec Indent a MarginLeft (tak, jak PowerPoint dělá, když vypnete odrážky/číslování odstavců). Posuny odsazení jsou aplikovány s ohledem na aktuální kontext odrážky – IBulletFormat.Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (výsledné hodnoty jsou lokální).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Volání této metody nemá význam a vyhodí **System.InvalidOperationException** v následujících případech:<br/>            pokud rodičovský formátovaný objekt není odstavcem (například volání ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() vyhodí výjimku);<br/>            nebo pokud odstavec nebyl přidán do jakékoli kolekce ITextFrame.Paragraphs (přidejte jej nejprve); |

### Viz také
* třída [`IBulletFormat`](/slides/python-net/cs/aspose.slides/ibulletformat)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)