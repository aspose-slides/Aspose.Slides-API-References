---
title: GetSensitivityLabels()
second_title: Aspose.Slides для C++ справочник API
description: Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /ru/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() метод

Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Примечания

Следующий код показывает, как переместить информацию о метках чувствительности из пользовательских свойств документа в современную коллекцию SensitivityLabels:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Получить метки чувствительности из пользовательских свойств документа
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Добавить метку в коллекцию
    // Здесь вы можете добавить проверку достоверности информации о метке (метка доступна и т.д.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISensitivityLabel](../../isensitivitylabel/)
* Класс [DocumentProperties](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)