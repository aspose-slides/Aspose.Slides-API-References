---
title: AddTextFrame()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет новый TextFrame к фигуре. Если у фигуры уже есть TextBox, то просто изменяет её текст.
type: docs
weight: 66
url: /ru/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) метод


Добавляет новый [TextFrame](../../textframe/) к фигуре. Если у фигуры уже есть [TextFrame](../../textframe/), то просто изменяет её текст.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст по умолчанию для нового [TextFrame](../../textframe/). |
## Примечания



В следующем примере кода показано, как добавить водяной знак в PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 В следующем примере показано, как создать Text Box на [Slide](../../slide/). 
```cpp
// Создаёт объект Presentation
auto pres = System::MakeObject<Presentation>();

// Получает первый слайд презентации
auto slide = pres->get_Slides()->idx_get(0);
// Добавляет AutoShape с типом Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Добавляет TextFrame в Rectangle
shape->AddTextFrame(u" ");
// Получает доступ к TextFrame
auto txtFrame = shape->get_TextFrame();
// Создаёт объект Paragraph для TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Создаёт объект Portion для Paragraph
auto portion = para->get_Portions()->idx_get(0);
// Устанавливает текст
portion->set_Text(u"Aspose TextBox");
// Сохраняет презентацию на диск
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 В следующем примере показано, как добавить колонку в Text Box. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Получает первый слайд презентации
auto slide = presentation->get_Slides()->idx_get(0);
// Добавляет AutoShape с типом Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Добавляет TextFrame в Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Получает формат текста TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Указывает количество колонок в TextFrame
format->set_ColumnCount(3);
// Указывает расстояние между колонками
format->set_ColumnSpacing(10);
// Сохраняет презентацию
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITextFrame](../../itextframe/)
* Класс [String](../../../system/string/)
* Класс [AutoShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)