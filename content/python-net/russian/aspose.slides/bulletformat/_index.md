---
title: BulletFormat class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/bulletformat/
---
## BulletFormat класс

Представляет свойства форматирования маркеров абзаца.

**Наследование:**[`BulletFormat`](/slides/python-net/ru/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип BulletFormat раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`type`](/slides/python-net/ru/aspose.slides/bulletformat/type/) | Возвращает или задаёт тип маркера абзаца без наследования.<br/>            Чтение/запись [`BulletType`](/slides/python-net/ru/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ru/aspose.slides/bulletformat/char/) | Возвращает или задаёт символ маркера абзаца без наследования.<br/>            Чтение/запись **System.Char**. |
| [`font`](/slides/python-net/ru/aspose.slides/bulletformat/font/) | Возвращает или задаёт шрифт маркера абзаца без наследования.<br/>            Чтение/запись [`IFontData`](/slides/python-net/ru/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ru/aspose.slides/bulletformat/height/) | Возвращает или задаёт высоту маркера абзаца без наследования.<br/>            Значение float.NaN определяет, что высота маркера наследуется от первой части абзаца.<br/>            Чтение/запись **float**. |
| [`color`](/slides/python-net/ru/aspose.slides/bulletformat/color/) | Возвращает формат цвета маркера абзаца без наследования.<br/>            Только чтение [`IColorFormat`](/slides/python-net/ru/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/ru/aspose.slides/bulletformat/numbered_bullet_start_with/) | Возвращает или задаёт первое число, используемое для группы нумерованных маркеров без наследования.<br/>            Чтение/запись **int**. |
| [`numbered_bullet_style`](/slides/python-net/ru/aspose.slides/bulletformat/numbered_bullet_style/) | Возвращает или задаёт стиль нумерованного маркера без наследования.<br/>            Чтение/запись [`NumberedBulletStyle`](/slides/python-net/ru/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/ru/aspose.slides/bulletformat/is_bullet_hard_color/) | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца.<br/>            **NullableBool.True**  если маркер имеет собственный цвет и **NullableBool.False**  если маркер<br/>            наследует цвет от первой части абзаца.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ru/aspose.slides/bulletformat/is_bullet_hard_font/) | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца.<br/>            **NullableBool.True**  если маркер имеет собственный шрифт и **NullableBool.False**  если маркер<br/>            наследует шрифт от первой части абзаца.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/ru/aspose.slides/bulletformat/picture/) | Возвращает изображение, используемое в качестве маркера в абзаце без наследования.<br/>            Только чтение [`ISlidesPicture`](/slides/python-net/ru/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/ru/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/bulletformat/presentation/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ru/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Устанавливает значения сдвигов по умолчанию, отличные от нуля, для эффективного отступа абзаца (Indent) и левого поля (MarginLeft), когда маркеры включены (как делает PowerPoint при включении маркеров/нумерации абзаца). Если маркеры отключены, то просто сбрасывает отступ абзаца и левое поле (как делает PowerPoint при отключении маркеров/нумерации абзаца). Сдвиги отступов применяются с учётом текущего контекста маркера — IBulletFormat.Type, .NumberedBulletStyle и высоты шрифта первой части. Сдвиги, отличные от нуля, применяются к эффективному Indent и MarginLeft текущего абзаца (делают полученные значения локальными). |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/bulletformat/get_effective/#) | Получает данные эффективного форматирования маркера с применённым наследованием. |

### См. также
* класс [`BulletFormat`](/slides/python-net/ru/aspose.slides/bulletformat)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)