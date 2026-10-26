---
title: get_ParagraphFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Formatierungsobjekt für diesen Absatz zurück. Nur lesbar IParagraphFormat.
type: docs
weight: 14
url: /de/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() Methode

Gibt das Formatierungsobjekt für diesen Absatz zurück. Nur lesbar [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Hinweise

Das Formatierungsobjekt enthält nur die für den aktuellen Absatz definierten Formatierungsparameter; vererbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der geerbten zu erhalten, verwenden Sie die [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) Methode.
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraphFormat](../../iparagraphformat/)
* Klasse [Paragraph](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)