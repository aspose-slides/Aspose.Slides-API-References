---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API Reference
description: Returns the parent cell or null if the parent object does not implement the ICell interface. Read-only ICell.
type: docs
weight: 79
url: /aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() method


Returns the parent cell or null if the parent object does not implement the [ICell](../../icell/) interface. Read-only [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Remarks


The following code sample shows 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)