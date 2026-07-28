---
title: get_ParentCell()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca komórkę nadrzędną lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. Tylko do odczytu ICell.
type: docs
weight: 105
url: /pl/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() method

Zwraca komórkę nadrzędną lub null, jeśli obiekt nadrzędny nie implementuje interfejsu [ICell](../../icell/). Tylko do odczytu [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Uwagi

Przykładowy fragment kodu pokazuje
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICell](../../icell/)
* Klasa [TextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)