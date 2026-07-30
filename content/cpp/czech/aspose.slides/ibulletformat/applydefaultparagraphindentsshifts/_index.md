---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Nastaví výchozí nenulové posuny pro efektivní Indent a MarginLeft odstavce, když jsou odrážky povoleny (jako v PowerPointu při zapnutí odrážek/číslování odstavců). Pokud jsou odrážky zakázány, pouze resetuje Indent a MarginLeft odstavce (jako v PowerPointu při vypnutí odrážek/číslování odstavců). Posuny odsazení jsou aplikovány s ohledem na aktuální kontext odrážky – IBulletFormat::get(set)_Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (výsledné hodnoty se stanou lokálními hodnotami)."
type: docs
weight: 235
url: /cs/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() metoda

Nastaví výchozí nenulové posuny pro efektivní Indent a MarginLeft odstavce, když jsou odrážky povoleny (podobně jako PowerPoint dělá, pokud zapnete odrážky/číslování odstavců). Pokud jsou odrážky zakázány, pak prostě resetuje Indent a MarginLeft odstavce (podobně jako PowerPoint dělá, pokud zakážete odrážky/číslování odstavců). Posuny odsazení jsou aplikovány s ohledem na aktuální kontext odrážky – IBulletFormat::get(set)_Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (výsledné hodnoty se stávají lokálními hodnotami).

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## Viz také

* Třída [IBulletFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)