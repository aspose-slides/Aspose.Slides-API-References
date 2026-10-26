---
title: FoundResult()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Metoda zpětného volání, která přijímá data o nalezeném textu.
type: docs
weight: 1
url: /cs/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) metoda

Metoda zpětného volání, která přijímá data o nalezeném textu.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | [ITextFrame](../../itextframe/), ve kterém byl text nalezen. |
| sourceText | [System::String](../../../system/string/) | Zdrojový text, ve kterém byl text nalezen. |
| foundText | [System::String](../../../system/string/) | Nalezený text. |
| textPosition | **int32_t** | Pozice nalezeného textu. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ITextFrame](../../itextframe/)
* Třída [String](../../../system/string/)
* Třída [IFindResultCallback](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)