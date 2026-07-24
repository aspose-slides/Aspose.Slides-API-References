---
title: UpdateDocumentProperties()
second_title: Aspose.Slides für C++ API Referenz
description: Aktualisiert die Eigenschaften der gebundenen Präsentation.
type: docs
weight: 92
url: /de/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method


Aktualisiert die Eigenschaften der gebundenen Präsentation.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Dokumenteigenschaften [IDocumentProperties](../../idocumentproperties/) |
## Bemerkungen



Dieses Beispiel zeigt, wie die [IPresentationInfo::UpdateDocumentProperties](./)-Methode aufgerufen wird, um die Dokumenteigenschaften zu aktualisieren, die durch den Aufruf der [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/)-Methode zurückgegeben werden. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDocumentProperties](../../idocumentproperties/)
* Klasse [IPresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)