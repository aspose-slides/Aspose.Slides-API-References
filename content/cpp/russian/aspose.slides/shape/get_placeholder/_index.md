---
title: get_Placeholder()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения IPlaceholder.
type: docs
weight: 14
url: /ru/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() метод

Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Замечания

В следующем примере показано, как изменить Text в [Placeholder](../../placeholder/).
```cpp
// Создает экземпляр класса Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Получает первый слайд
auto slide = pres->get_Slides()->idx_get(0);

// Итерируется по фигурам, чтобы найти заполнитель
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // Изменяет текст в каждом заполнителе
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// Сохраняет презентацию на диск
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
В следующем примере показано, как задать Prompt Text в [Placeholder](../../placeholder/).
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPlaceholder](../../iplaceholder/)
* Класс [Shape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)