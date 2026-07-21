---
title: UpdateDocumentProperties()
second_title: Справочник API Aspose.Slides для C++
description: Обновляет свойства привязанной презентации.
type: docs
weight: 92
url: /ru/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) метод

Обновляет свойства привязанной презентации.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Примечания

Этот пример показывает, как вызвать метод [PresentationInfo::UpdateDocumentProperties](./) для обновления свойств документа, возвращаемых вызовом метода [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IDocumentProperties](../../idocumentproperties/)
* Класс [PresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)