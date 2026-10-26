---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API 参考
description: 返回父单元格，如果父对象未实现 ICell 接口，则返回 null。只读 ICell。
type: docs
weight: 79
url: /zh/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() 方法


返回父单元格，如果父对象未实现 [ICell](../../icell/) 接口，则返回 null。只读 [ICell](../../icell/)。

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## 备注


以下代码示例显示 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICell](../../icell/)
* 类 [ITextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)