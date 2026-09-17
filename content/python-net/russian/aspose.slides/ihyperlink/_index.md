---
title: IHyperlink class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ihyperlink/
---
## IHyperlink класс

Представляет гиперссылку.

Тип IHyperlink предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`action_type`](/slides/python-net/ru/aspose.slides/ihyperlink/action_type/) | Возвращает тип действия HyperLinkEx.<br/>            Только для чтения [`HyperlinkActionType`](/slides/python-net/ru/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ru/aspose.slides/ihyperlink/external_url/) | Указывает внешний URL<br/>            Если это свойство не None, то свойство TargetSlide становится None.<br/>            Только для чтения **str**. |
| [`external_url_original`](/slides/python-net/ru/aspose.slides/ihyperlink/external_url_original/) | Представляет гиперссылку, установленную для этой части независимо от фактического содержимого части.<br/>            <br/>            PowerPoint обрабатывает ссылки и их соответствующий текст в части особым образом. Он позволяет создавать текст гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство представляет исходное значение гиперссылки. |
| [`target_slide`](/slides/python-net/ru/aspose.slides/ihyperlink/target_slide/) | Если HyperlinkEx указывает на конкретный слайд, возвращает этот слайд.<br/>            Если свойство не None, то свойство ExternalUrl становится None.<br/>            Только для чтения [`ISlide`](/slides/python-net/ru/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/ru/aspose.slides/ihyperlink/target_frame/) | Возвращает кадр внутри родительского HTML-frameset для цели<br/>            родительской гиперссылки, если он существует.<br/>            Чтение/запись **str**. |
| [`tooltip`](/slides/python-net/ru/aspose.slides/ihyperlink/tooltip/) | Возвращает строку, которая может отображаться в пользовательском интерфейсе<br/>            как связанная с родительской гиперссылкой.<br/>            Чтение/запись **str**. |
| [`history`](/slides/python-net/ru/aspose.slides/ihyperlink/history/) | Определяет, будет ли цель родительской гиперссылки добавлена<br/>            в список просмотренных гиперссылок при её вызове.<br/>            Чтение/запись **bool**. |
| [`highlight_click`](/slides/python-net/ru/aspose.slides/ihyperlink/highlight_click/) | Определяет, должна ли гиперссылка выделяться при клике.<br/>            Чтение/запись **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ru/aspose.slides/ihyperlink/stop_sound_on_click/) | Определяет, должен ли звук останавливаться при клике по гиперссылке.<br/>            Чтение/запись **bool**. |
| [`sound`](/slides/python-net/ru/aspose.slides/ihyperlink/sound/) | Представляет воспроизводимый звук гиперссылки.<br/>            Чтение/запись [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ru/aspose.slides/ihyperlink/color_source/) | Представляет источник цвета гиперссылки — стили или формат части.<br/>            Чтение/запись [`HyperlinkColorSource`](/slides/python-net/ru/aspose.slides/hyperlinkcolorsource). |

## Методы

| Метод | Описание |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ru/aspose.slides/ihyperlink/equals/#ihyperlink) | Определяет, равны ли два экземпляра Hyperlink. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)