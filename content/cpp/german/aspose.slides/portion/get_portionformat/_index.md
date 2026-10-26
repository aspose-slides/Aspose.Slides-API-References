---
title: get_PortionFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts ohne angewendete Vererbung enthält. Nur lesbar IPortionFormat.
type: docs
weight: 1
url: /de/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() Methode

Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. Nur lesbar [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Anmerkungen

Das Formatierungsobjekt enthält nur die für den aktuellen Abschnitt definierten Formatierungsparameter, vererbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der vererbten zu erhalten, verwenden Sie die [PortionFormat::GetEffective](../../portionformat/geteffective/) Methode.

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormat](../../iportionformat/)
* Klasse [Portion](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)