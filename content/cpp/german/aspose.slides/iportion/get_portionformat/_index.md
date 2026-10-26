---
title: get_PortionFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Formatierungsobjekt zurück, das die explizit festgelegten Formatierungseigenschaften des Textabschnitts ohne angewandte Vererbung enthält. Nur lesbar IPortionFormat.
type: docs
weight: 1
url: /de/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() Methode

Gibt ein Formatierungsobjekt zurück, das die explizit festgelegten Formatierungseigenschaften des Textabschnitts ohne angewandte Vererbung enthält. Nur lesbar [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Hinweise

Das Formatierungsobjekt enthält die für den aktuellen Abschnitt definierten Formatierungsparameter; vererbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich vererbter Werte zu erhalten, verwenden Sie die [IPortionFormat::GetEffective](../../iportionformat/geteffective/) Methode.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormat](../../iportionformat/)
* Klasse [IPortion](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)