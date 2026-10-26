---
title: SetMacroHyperlinkClick()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает гиперссылку макроса по щелчку.
type: docs
weight: 79
url: /ru/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) method


Устанавливает гиперссылку макроса по щелчку.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Имя макроса |

### Возвращаемое значение

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IHyperlink](../../ihyperlink/)
* Класс [String](../../../system/string/)
* Класс [HyperlinkManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)