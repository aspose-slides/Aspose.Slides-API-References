---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides для C++ API справка
description: Устанавливает внешнюю гиперссылку при щелчке.
type: docs
weight: 1
url: /ru/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) метод

Устанавливает внешнюю гиперссылку при щелчке.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Примечания

Следующий пример кода показывает, как добавить Text Box с [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Получает первый слайд в презентации
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Добавляет объект AutoShape с типом Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Доступ к свойству ITextFrame, связанному с AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Добавляет некоторый текст во фрейм
portion->set_Text(u"Aspose.Slides");

// Устанавливает гиперссылку для текста части
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Сохраняет PPTX презентацию
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IHyperlink](../../ihyperlink/)
* Класс [String](../../../system/string/)
* Класс [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)