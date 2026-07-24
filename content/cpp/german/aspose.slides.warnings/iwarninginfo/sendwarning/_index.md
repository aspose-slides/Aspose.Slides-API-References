---
title: SendWarning()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn receiver nicht null ist, beendet die Warnung an einen angegebenen Empfänger und wirft die AbortRequestedException, wenn receiver beschlossen hat, den Vorgang abzubrechen.
type: docs
weight: 27
url: /de/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) Methode


Wenn receiver nicht null ist, beendet die Warnung an einen angegebenen Empfänger und wirft die AbortRequestedException, wenn receiver beschlossen hat, den Vorgang abzubrechen.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Empfängerobjekt [IWarningCallback](../../iwarningcallback/) |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IWarningCallback](../../iwarningcallback/)
* Klasse [IWarningInfo](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Bibliothek [Aspose.Slides](../../../)