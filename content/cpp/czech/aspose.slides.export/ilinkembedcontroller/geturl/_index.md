---
title: GetUrl()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Vrací URL na externí objekt. Tato metoda je vždy volána, pokud ILinkEmbedController::GetObjectStoringLocation vrátil LinkEmbedDecision::Link, a může být volána, pokud ILinkEmbedController::GetObjectStoringLocation vrátil LinkEmbedDecision::Embed, ale vložení je nemožné. Může být volána vícekrát pro stejné ID objektu."
type: docs
weight: 14
url: /cs/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metoda


Vrací URL na externí objekt. Tato metoda je vždy volána, pokud [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) vrátil [LinkEmbedDecision::Link](../../linkembeddecision/), a může být volána, pokud [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) vrátil [LinkEmbedDecision::Embed](../../linkembeddecision/), ale vkládání je nemožné. Může být volána vícekrát pro stejné ID objektu.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | **int32_t** | ID objektu. Toto ID je během celého operace jedinečné. |
| referrer | **int32_t** | ID odkazujícího objektu nebo 0, pokud je objekt odkazován kořenovým dokumentem. Může být použito k vytvoření relativního odkazu. |

### Návratová hodnota

URL externího objektu nebo null, pokud má být tento objekt ignorován.

## Viz také

* Třída [String](../../../system/string/)
* Třída [ILinkEmbedController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)