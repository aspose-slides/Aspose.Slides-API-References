---
title: Warning()
second_title: Aspose.Slides för C++ API-referens
description: Callback-metod som tar emot en varning och avgör om operationen ska avbrytas.
type: docs
weight: 1
url: /sv/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metod


Callback-metod som tar emot en varning och avgör om operationen ska avbrytas.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Varning att behandla. |

### Returvärde

Abortbeslut [ReturnAction](../../returnaction/).

## Se även

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IWarningInfo](../../iwarninginfo/)
* Klass [IWarningCallback](../)
* Namnrymd [Aspose::Slides::Warnings](../../)
* Bibliotek [Aspose.Slides](../../../)