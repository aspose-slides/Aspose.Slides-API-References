---
title: Warning()
second_title: Aspose.Slides voor C++ API-referentie
description: Callback-methode die een waarschuwing ontvangt en beslist of de bewerking moet worden afgebroken.
type: docs
weight: 1
url: /nl/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) methode

Callback-methode die een waarschuwing ontvangt en beslist of de bewerking moet worden afgebroken.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Waarschuwing die verwerkt moet worden. |

### Retourwaarde

Abortbeslissing [ReturnAction](../../returnaction/).

## Zie ook

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IWarningInfo](../../iwarninginfo/)
* Klasse [IWarningCallback](../)
* Naamruimte [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)