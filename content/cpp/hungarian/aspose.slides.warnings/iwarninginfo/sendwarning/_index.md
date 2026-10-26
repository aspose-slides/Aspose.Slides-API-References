---
title: SendWarning()
second_title: Aspose.Slides C++ API hivatkozás
description: Ha a receiver nem null, befejezi a figyelmeztetést egy meghatározott receivernek, és AbortRequestedException-t dob, ha a receiver úgy dönt, hogy megszakít egy műveletet.
type: docs
weight: 27
url: /hu/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) metódus


Ha a receiver nem null, befejezi a figyelmeztetést egy megadott receivernek, és AbortRequestedException-t dob, ha a receiver úgy dönt, hogy megszakítja a műveletet.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Receiver objektum [IWarningCallback](../../iwarningcallback/) |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IWarningCallback](../../iwarningcallback/)
* Osztály [IWarningInfo](../)
* Névterület [Aspose::Slides::Warnings](../../)
* Könyvtár [Aspose.Slides](../../../)