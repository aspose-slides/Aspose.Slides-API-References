---
title: Warning()
second_title: Aspose.Slides pro C++ API Reference
description: Metoda zpětného volání, která přijímá varování a rozhoduje, zda má být operace přerušena.
type: docs
weight: 1
url: /cs/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metoda


Metoda zpětného volání, která přijímá varování a rozhoduje, zda má být operace přerušena.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Varování ke zpracování. |

### Návratová hodnota

Rozhodnutí o přerušení [ReturnAction](../../returnaction/).

## Viz také

* Výčet [ReturnAction](../../returnaction/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IWarningInfo](../../iwarninginfo/)
* Třída [IWarningCallback](../)
* Jmenný prostor [Aspose::Slides::Warnings](../../)
* Knihovna [Aspose.Slides](../../../)