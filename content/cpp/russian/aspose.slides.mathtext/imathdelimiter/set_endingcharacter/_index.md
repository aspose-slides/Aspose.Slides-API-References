---
title: set_EndingCharacter()
second_title: Aspose.Slides для C++ – справочник API
description: "Символ завершения разделителя определяет конечный, или закрывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'."
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) метод

Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Замечания


Пример: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## См. также

* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)