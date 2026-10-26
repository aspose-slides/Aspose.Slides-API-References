---
title: get_ParentCell()
second_title: Aspose.Slides для C++ справка API
description: Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения ICell.
type: docs
weight: 79
url: /ru/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() метод


Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс [ICell](../../icell/). Только для чтения [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Примечания


Следующий пример кода показывает 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ICell](../../icell/)
* Класс [ITextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)