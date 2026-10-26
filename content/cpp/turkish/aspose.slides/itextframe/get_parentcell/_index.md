---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API Referansı
description: Üst hücreyi döndürür veya üst nesne ICell arayüzünü uygulamıyorsa null döndürür. Salt okunur ICell.
type: docs
weight: 79
url: /tr/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metodu

Üst hücreyi döndürür veya üst nesne [ICell](../../icell/) arayüzünü uygulamıyorsa null döndürür. Salt okunur [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Açıklamalar

Aşağıdaki kod örneği gösterir

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICell](../../icell/)
* Sınıf [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)