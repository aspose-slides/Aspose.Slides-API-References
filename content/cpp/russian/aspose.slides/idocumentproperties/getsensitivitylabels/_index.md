---
title: GetSensitivityLabels()
second_title: Aspose.Slides для C++ справочник API
description: Получает массив меток конфиденциальности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /ru/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() метод


Получает массив меток конфиденциальности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Примечания


Следующий код показывает, как перенести информацию о метках конфиденциальности из пользовательских свойств документа в современную коллекцию SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Получить метки конфиденциальности из пользовательских свойств документа
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Добавить метку в коллекцию
    // Здесь вы можете добавить проверку действительности информации о метке (метка доступна и т.д.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISensitivityLabel](../../isensitivitylabel/)
* Класс [IDocumentProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)