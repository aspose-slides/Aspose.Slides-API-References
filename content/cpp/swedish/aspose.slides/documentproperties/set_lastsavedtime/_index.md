---
title: set_LastSavedTime()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Skrivrättighetsbegränsad vid Presentation::get_DocumentProperties (eftersom den kommer att uppdateras internt under IPresentation-objektets sparprocess). Kan ändras via DocumentProperties-instans som returneras av metoden IPresentationInfo::ReadDocumentProperties. Se gärna exemplet i metodsammanfattningen för IPresentationInfo::UpdateDocumentProperties."
type: docs
weight: 391
url: /sv/aspose.slides/documentproperties/set_lastsavedtime/
---
## DocumentProperties::set_LastSavedTime(System::DateTime) metod


Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Skrivskyddad i fall av [Presentation::get_DocumentProperties](../../presentation/get_documentproperties/) (eftersom den kommer att uppdateras internt medan [IPresentation](../../ipresentation/)-objektets sparprocess). Kan ändras via [DocumentProperties](../) instans som returneras av metod [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) Se gärna exemplet i [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) metodsammanfattning.

```cpp
void Aspose::Slides::DocumentProperties::set_LastSavedTime(System::DateTime value) override
```

## Se även

* Klass [DateTime](../../../system/datetime/)
* Klass [DocumentProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)