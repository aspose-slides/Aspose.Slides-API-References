---
title: set_SpellCheck()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию — false.
type: docs
weight: 612
url: /ru/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) метод


Устанавливает значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию — **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Примечания


Следующий пример демонстрирует включение флага SpellCheck перед сохранением презентации: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Доступ к первой части текста внутри первой фигуры на первом слайде
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Включить проверку орфографии для этой части текста
portion->get_PortionFormat()->set_SpellCheck(true);
// Сохранить изменённую презентацию
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [IBasePortionFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)