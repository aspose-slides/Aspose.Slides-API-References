---
title: GetObjectStoringLocation()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, kde by měl být objekt uložen. Tato metoda je volána jednou pro každé ID objektu. Není zaručeno, že nebudou existovat dva objekty se stejnými daty, semanticName a contentType, ale s odlišným ID.
type: docs
weight: 1
url: /cs/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metoda


Určuje, kde by měl být objekt uložen. Tato metoda je volána jednou pro každé ID objektu. Není zaručeno, že nebudou existovat dva objekty se stejnými daty, semanticName a contentType, ale s odlišným ID.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | **int32_t** | ID objektu. Toto ID je v rámci operace ukládání jedinečné. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Binární data objektu. Tento parametr může být null, pokud binární data objektu ještě nebyla vygenerována. |
| semanticName | [System::String](../../../system/string/) | Krátký text popisující význam objektu. Kontroler jej může použít jako součást externího názvu objektu, ale je na dispatcherovi, aby zajistil, že názvy budou jedinečné a budou obsahovat pouze povolené znaky. |
| contentType | [System::String](../../../system/string/) | MIME typ objektu. |
| recomendedExtension | [System::String](../../../system/string/) | Přípona souboru doporučená pro tento MIME typ. |

### Návratová hodnota

Decision

## Viz také

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [ILinkEmbedController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)