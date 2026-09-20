---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Nastaví výchozí nenulové posuny pro efektivní odstavec Indent a MarginLeft, když jsou odrážky povoleny (jako to dělá PowerPoint, pokud povolíte odrážky/číslování odstavců). Pokud jsou odrážky zakázány, prostě resetuje odstavec Indent a MarginLeft (jako to dělá PowerPoint, pokud zakážete odrážky/číslování odstavců). Posuny odsazení se aplikují s ohledem na aktuální kontext odrážky – IBulletFormat.Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení se aplikují na efektivní Indent a MarginLeft aktuálního odstavce (aby výsledné hodnoty byly lokální).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Volání této metody nemá smysl a vyvolá **System.InvalidOperationException** v následujících případech:<br/>            pokud rodičovský formátovaný objekt není odstavcem (například volání ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() vyvolá výjimku);<br/>            nebo pokud odstavec nebyl přidán do žádné kolekce ITextFrame.Paragraphs (přidejte jej nejprve); |



### Viz také
* třída [`BulletFormat`](/slides/python-net/cs/aspose.slides/bulletformat)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)