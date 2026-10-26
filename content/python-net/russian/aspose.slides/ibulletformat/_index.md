---
title: IBulletFormat class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/ibulletformat/
---
## IBulletFormat класс

Представляет свойства форматирования маркеров абзаца.

Тип IBulletFormat раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`type`](/slides/python-net/ru/aspose.slides/ibulletformat/type/) | Возвращает или задаёт тип маркера абзаца без наследования.<br/>            Чтение/запись [`BulletType`](/slides/python-net/ru/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ru/aspose.slides/ibulletformat/char/) | Возвращает или задаёт символ маркера абзаца без наследования.<br/>            Чтение/запись **System.Char**. |
| [`font`](/slides/python-net/ru/aspose.slides/ibulletformat/font/) | Возвращает или задаёт шрифт маркера абзаца без наследования.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ru/aspose.slides/ibulletformat/height/) | Возвращает или задаёт высоту маркера абзаца без наследования.<br/>            Значение float.NaN указывает, что высота маркера наследуется от первой части абзаца.<br/>            Чтение/запись **float**. |
| [`color`](/slides/python-net/ru/aspose.slides/ibulletformat/color/) | Возвращает формат цвета маркера абзаца без наследования.<br/>            Только чтение [`IColorFormat`](/slides/python-net/ru/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/ru/aspose.slides/ibulletformat/picture/) | Возвращает изображение, используемое в качестве маркера в абзаце без наследования.<br/>            Только чтение [`ISlidesPicture`](/slides/python-net/ru/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/ru/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Возвращает или задаёт первый номер, используемый для группы нумерованных маркеров без наследования.<br/>            Чтение/запись **int**. |
| [`numbered_bullet_style`](/slides/python-net/ru/aspose.slides/ibulletformat/numbered_bullet_style/) | Возвращает или задаёт стиль нумерованного маркера без наследования.<br/>            Чтение/запись [`IBulletFormat.numbered_bullet_style`](/slides/python-net/ru/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/ru/aspose.slides/ibulletformat/is_bullet_hard_color/) | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца.<br/>            **NullableBool.True**  если маркер имеет собственный цвет и **NullableBool.False**  если маркер<br/>            наследует цвет от первой части абзаца.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ru/aspose.slides/ibulletformat/is_bullet_hard_font/) | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца.<br/>            **NullableBool.True**  если маркер имеет собственный шрифт и **NullableBool.False**  если маркер<br/>            наследует шрифт от первой части абзаца.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |

## Методы

| Метод | Описание |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ru/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Устанавливает значения смещений по умолчанию, отличные от нуля, для эффективных параметров абзаца Indent и MarginLeft, когда маркеры включены (как делает PowerPoint при включении маркеров/нумерации абзаца). Если маркеры отключены, просто сбрасывает параметры абзаца Indent и MarginLeft (как делает PowerPoint при отключении маркеров/нумерации абзаца). Смещения отступов применяются с учётом текущего контекста маркера — IBulletFormat.Type, .NumberedBulletStyle и FontHeight первой части. Смещения, отличные от нуля, применяются к эффективным Indent и MarginLeft текущего абзаца (делая полученные значения локальными). |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/ibulletformat/get_effective/#) | Получает эффективные данные форматирования маркера с учётом применённого наследования. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)