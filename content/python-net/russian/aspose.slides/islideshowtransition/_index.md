---
title: ISlideShowTransition class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/islideshowtransition/
---
## ISlideShowTransition класс

Представляет переход слайд-шоу.

Тип ISlideShowTransition раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound/) | Возвращает или задает встроенные аудиоданные.<br/>            Чтение-запись [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound_mode/) | Устанавливает или возвращает режим звучания для перехода слайда.<br/>            Чтение-запись [`TransitionSoundMode`](/slides/python-net/ru/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound_loop/) | Этот атрибут указывает, будет ли звук повторяться до наступления следующего звукового события в<br/>            слайд-шоу.<br/>            Чтение-запись **bool**. |
| [`advance_on_click`](/slides/python-net/ru/aspose.slides/islideshowtransition/advance_on_click/) | Указывает, будет ли щелчок мыши переключать слайд или нет. Если этот атрибут не<br/>            указан, предполагается значение true.<br/>            Чтение-запись **bool**. |
| [`advance_after`](/slides/python-net/ru/aspose.slides/islideshowtransition/advance_after/) | Этот атрибут указывает, будет ли презентация переходить к следующему слайду через определённое время.<br/>            Чтение/запись **bool**. |
| [`advance_after_time`](/slides/python-net/ru/aspose.slides/islideshowtransition/advance_after_time/) | Указывает время в миллисекундах, после которого должен начаться переход. Эта настройка<br/>            может использоваться совместно с атрибутом advClick. Если этот атрибут не указан,<br/>            считается, что авто-переход не будет происходить.<br/>            Чтение-запись **int**. |
| [`speed`](/slides/python-net/ru/aspose.slides/islideshowtransition/speed/) | Указывает скорость перехода, которая будет использоваться при переходе от текущего слайда<br/>            к следующему.<br/>            Чтение-запись [`TransitionSpeed`](/slides/python-net/ru/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/ru/aspose.slides/islideshowtransition/value/) | Значение перехода слайд-шоу.<br/>            Только чтение [`ITransitionValueBase`](/slides/python-net/ru/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/ru/aspose.slides/islideshowtransition/type/) | Тип перехода.<br/>            Чтение-запись [`TransitionType`](/slides/python-net/ru/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound_is_built_in/) | Указывает, является ли звук встроенным. Если этот атрибут установлен в true, то<br/>            генерирующее приложение получает сигнал проверить атрибут name, указанный для этого звука<br/>            в его списке встроенных звуков, и может отобразить пользовательское имя или интерфейс при необходимости.<br/>            Чтение-запись **bool**. |
| [`sound_name`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound_name/) | Указывает человекочитаемое имя звука перехода. Свойство [`ISlideShowTransition.sound`](/slides/python-net/ru/aspose.slides/islideshowtransition/sound) должно быть назначено для получения или установки имени звука.<br/>            Чтение-запись **str**. |
| [`duration`](/slides/python-net/ru/aspose.slides/islideshowtransition/duration/) | Получает или задает длительность эффекта перехода слайда в миллисекундах.<br/>            Чтение/запись **int**. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)