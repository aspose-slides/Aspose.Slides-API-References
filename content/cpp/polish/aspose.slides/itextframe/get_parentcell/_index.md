---
title: get_ParentCell()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca rodzicielską komórkę lub null, jeśli obiekt nadrzędny nie implementuje interfejsu ICell. Tylko do odczytu ICell.
type: docs
weight: 79
url: /pl/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metoda


Zwraca rodzicowską komórkę lub null, jeśli obiekt nadrzędny nie implementuje interfejsu [ICell](../../icell/). Tylko do odczytu [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Uwagi


Poniższy przykład kodu pokazuje 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICell](../../icell/)
* Klasa [ITextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)