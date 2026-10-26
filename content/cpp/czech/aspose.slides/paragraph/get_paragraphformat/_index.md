---
title: get_ParagraphFormat()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vrací objekt formátování pro tento odstavec. Pouze ke čtení IParagraphFormat.
type: docs
weight: 14
url: /cs/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() metoda

Vrací objekt formátování pro tento odstavec. Pouze ke čtení [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Poznámky

Objekt formátování obsahuje pouze formátovací parametry definované pro aktuální odstavec, zděděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IParagraphFormat](../../iparagraphformat/)
* Třída [Paragraph](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)