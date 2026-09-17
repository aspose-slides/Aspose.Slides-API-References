---
title: SwfOptions class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/swfoptions/
---
## SwfOptions класс

Предоставляет параметры, контролирующие, как презентация сохраняется в формате Swf.

Наследование:[`SwfOptions`](/slides/python-net/ru/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип SwfOptions раскрывает следующие члены:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/swfoptions/__init__/#) | Конструктор по умолчанию. |

## Свойства

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/swfoptions/warning_callback/) | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/swfoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/swfoptions/default_regular_font/) | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/swfoptions/gradient_style/) | Возвращает или устанавливает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/swfoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_hidden_slides/) | Указывает, следует ли включать скрытые слайды в сгенерированный документ.<br/>            По умолчанию `false`. |
| [`compressed`](/slides/python-net/ru/aspose.slides.export/swfoptions/compressed/) | Указывает, следует ли сжимать сгенерированный SWF-документ.<br/>            По умолчанию `true`. |
| [`viewer_included`](/slides/python-net/ru/aspose.slides.export/swfoptions/viewer_included/) | Указывает, следует ли включать в сгенерированный SWF-документ интегрированный просмотрщик документов.<br/>            По умолчанию `true`. |
| [`show_page_border`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_page_border/) | Указывает, следует ли отображать рамку вокруг страниц. По умолчанию true. |
| [`show_full_screen`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_full_screen/) | Отображать/скрывать кнопку полноэкранного режима. Может быть переопределено в flashvars. По умолчанию true. |
| [`show_page_stepper`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_page_stepper/) | Отображать/скрывать переключатель страниц. Может быть переопределено в flashvars. По умолчанию true. |
| [`show_search`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_search/) | Отображать/скрывать раздел поиска. Может быть переопределено в flashvars. По умолчанию true. |
| [`show_top_pane`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_top_pane/) | Отображать/скрывать всю верхнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [`show_bottom_pane`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_bottom_pane/) | Отображать/скрывать нижнюю панель. Может быть переопределено в flashvars. По умолчанию true. |
| [`show_left_pane`](/slides/python-net/ru/aspose.slides.export/swfoptions/show_left_pane/) | Отображать/скрывать левую панель. Может быть переопределено в flashvars. По умолчанию true. |
| [`start_open_left_pane`](/slides/python-net/ru/aspose.slides.export/swfoptions/start_open_left_pane/) | Запускать с открытой левой панелью. Может быть переопределено в flashvars. По умолчанию false. |
| [`enable_context_menu`](/slides/python-net/ru/aspose.slides.export/swfoptions/enable_context_menu/) | Включать/отключать контекстное меню. По умолчанию true. |
| [`logo_image_bytes`](/slides/python-net/ru/aspose.slides.export/swfoptions/logo_image_bytes/) | Изображение, которое будет отображаться в виде логотипа в правом верхнем углу просмотрщика.<br/>            Изображение должно быть PNG размером 32 × 64 пикселей, иначе логотип может отображаться некорректно. |
| [`logo_link`](/slides/python-net/ru/aspose.slides.export/swfoptions/logo_link/) | Получает или задает полный URL-адрес гиперссылки для логотипа.<br/>            Имеет эффект только если указано [`SwfOptions.logo_image_bytes`](/slides/python-net/ru/aspose.slides.export/swfoptions/logo_image_bytes). |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/swfoptions/jpeg_quality/) | Указывает качество JPEG-изображений.<br/>            По умолчанию 95. |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/swfoptions/slides_layout_options/) | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions).<br/>            Это свойство не поддерживает присвоение объектов типа [`HandoutLayoutingOptions`](/slides/python-net/ru/aspose.slides.export/handoutlayoutingoptions). |

### См. также
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* класс [`SwfOptions`](/slides/python-net/ru/aspose.slides.export/swfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)