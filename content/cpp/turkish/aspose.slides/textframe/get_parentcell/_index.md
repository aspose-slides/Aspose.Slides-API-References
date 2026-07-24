---
title: get_ParentCell()
second_title: Aspose.Slides için C++ API Referansı
description: Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa null döndürür. Salt okunur ICell.
type: docs
weight: 105
url: /tr/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() metodu


Üst hücreyi döndürür veya üst nesne [ICell](../../icell/) arayüzünü uygulamıyorsa null döndürür. Salt okunur [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Açıklamalar


Aşağıdaki kod örneği gösterir 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICell](../../icell/)
* Sınıf [TextFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)