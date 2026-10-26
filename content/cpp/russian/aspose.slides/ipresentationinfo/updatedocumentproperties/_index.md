---
title: UpdateDocumentProperties()
second_title: Aspose.Slides для C++: справка API
description: Обновляет свойства привязанной презентации.
type: docs
weight: 92
url: /ru/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) метод

Обновляет свойства привязанной презентации.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Свойства документа [IDocumentProperties](../../idocumentproperties/) |

## Примечания

Этот пример показывает, как вызвать метод [IPresentationInfo::UpdateDocumentProperties](./), чтобы обновить свойства документа, полученные вызовом метода [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IDocumentProperties](../../idocumentproperties/)
* Класс [IPresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)