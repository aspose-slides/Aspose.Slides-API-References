---
title: get_HeaderFooterManager()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текущий менеджер HeaderFooter. Только для чтения IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /ru/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() метод

Возвращает текущий менеджер HeaderFooter. Только для чтения [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Примечания

Следующий пример показывает, как установить видимость колонтитула внутри [Slide](../../slide/) PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Свойство IsFooterVisible используется для указания, что заполнитель нижнего колонтитула слайда отсутствует.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Метод SetFooterVisibility используется для отображения заполнителя нижнего колонтитула слайда.
    headerFooterManager->SetFooterVisibility(true);
}

// Свойство IsSlideNumberVisible используется для указания, что заполнитель номера страницы слайда отсутствует.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Метод SetSlideNumberVisibility используется для отображения заполнителя номера страницы слайда.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Свойство IsDateTimeVisible используется для указания, что заполнитель даты и времени слайда отсутствует.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Метод SetFooterVisibility используется для отображения заполнителя даты и времени слайда.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Метод SetFooterText используется для установки текста в заполнитель нижнего колонтитула слайда.
headerFooterManager->SetFooterText(u"Footer text");
// Метод SetDateTimeText используется для установки текста в заполнитель даты и времени слайда.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
Следующий пример показывает, как установить видимость дочернего колонтитула внутри [Slide](../../slide/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Метод SetFooterAndChildFootersVisibility используется для отображения мастер-слайда и всех дочерних заполнителей нижнего колонтитула.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Метод SetSlideNumberAndChildSlideNumbersVisibility используется для отображения мастер-слайда и всех дочерних заполнителей номеров страниц.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Метод SetDateTimeAndChildDateTimesVisibility используется для отображения мастер-слайда и всех дочерних заполнителей даты и времени.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Метод SetFooterAndChildFootersText используется для установки текста в мастер-слайд и все дочерние заполнители нижнего колонтитула.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Метод SetDateTimeAndChildDateTimesText используется для установки текста в мастер-слайд и все дочерние заполнители даты и времени.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)