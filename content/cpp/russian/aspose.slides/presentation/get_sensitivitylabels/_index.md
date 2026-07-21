---
title: get_SensitivityLabels()
second_title: Справка API Aspose.Slides для C++
description: Возвращает коллекцию меток чувствительности, применённых к документу презентации. Только для чтения ISensitivityLabelCollection.
type: docs
weight: 378
url: /ru/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() метод


Возвращает коллекцию меток чувствительности, примененных к документу презентации. Только для чтения [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Замечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Вывести применённые метки
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Добавить новую метку
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Получить идентификатор метки чувствительности из политики
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Получить идентификатор сайта Azure AD из политики
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Класс [Presentation](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)