---
title: ColorTranslator
second_title: Aspose.Slides для C++ справочника API
description: "Выполняет преобразование цветов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или ошибкам утверждения. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 66
url: /ru/system.drawing/colortranslator/
---
## ColorTranslator класс

Выполняет преобразование цветов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или ошибкам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorTranslator
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Преобразует заданное представление цвета в формате HTML в эквивалентный объект [Color](../color/). |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Преобразует указанный цвет [Windows](../../system.windows/) в эквивалентный объект [Color](../color/). |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Преобразует указанный объект [Color](../color/) в строковое представление эквивалентного цвета HTML. |

## См. также

* Пространство имён [System::Drawing](../)
* Библиотека [Aspose.Slides](../../)