---
title: SlideShowTransition class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition класс

Представляет переход слайд-шоу.

Тип SlideShowTransition раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`sound`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound/) | Возвращает или задаёт встроенные аудиоданные.<br/>            Чтение/запись [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Устанавливает или возвращает режим звука для перехода слайда.<br/>            Чтение/запись [`TransitionSoundMode`](/slides/python-net/ru/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Этот атрибут указывает, будет ли звук повторяться до наступления следующего звукового события в слайд-шоу.<br/>            Чтение/запись **bool**. |
| [`advance_on_click`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Указывает, будет ли клик мыши переключать слайд. Если атрибут не указан, подразумевается значение true.<br/>            Чтение/запись **bool**. |
| [`advance_after`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/advance_after/) | Этот атрибут указывает, будет ли слайд-шоу переходить к следующему слайду через определённое время.<br/>            Чтение/запись **bool**. |
| [`advance_after_time`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Указывает время в миллисекундах, после которого должен начаться переход. Эта настройка может использоваться совместно с атрибутом advClick. Если атрибут не указан, считается, что автоматическое переключение не происходит.<br/>            Чтение/запись **int**. |
| [`speed`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/speed/) | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему.<br/>            Чтение/запись [`TransitionSpeed`](/slides/python-net/ru/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/value/) | Значение перехода слайд-шоу.<br/>            Только для чтения [`ITransitionValueBase`](/slides/python-net/ru/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/type/) | Тип перехода.<br/>            Чтение/запись [`TransitionType`](/slides/python-net/ru/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Указывает, является ли этот звук встроенным. Если атрибут установлен в true, то генерирующее приложение проверяет атрибут name, указанный для этого звука, в списке встроенных звуков и может отобразить пользовательское имя или интерфейс при необходимости.<br/>            Чтение/запись **bool**. |
| [`sound_name`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound_name/) | Указывает человекочитаемое имя звука перехода. Свойство [`SlideShowTransition.sound`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/sound) должно быть назначено для получения или установки имени звука.<br/>            Чтение/запись **str**. |
| [`duration`](/slides/python-net/ru/aspose.slides.slideshow/slideshowtransition/duration/) | Получает или задаёт продолжительность эффекта перехода слайда в миллисекундах.<br/>            Чтение/запись **int**. |

### См. также
* модуль [`aspose.slides.slideshow`](/slides/python-net/ru/aspose.slides.slideshow)
* библиотека [`Aspose.Slides`](/slides/python-net)