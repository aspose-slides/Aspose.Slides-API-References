---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает гиперссылку на макрос при щелчке.
type: docs
weight: 79
url: /ru/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) метод


Устанавливает гиперссылку на макрос при щелчке.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Имя макроса |

### Возвращаемое значение

[Hyperlink](../../hyperlink/) объект [IHyperlink](../../ihyperlink/)
## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IHyperlink](../../ihyperlink/)
* Класс [String](../../../system/string/)
* Класс [IHyperlinkManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)