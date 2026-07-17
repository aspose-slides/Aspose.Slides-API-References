---
title: AddSection()
second_title: Aspose.Slides C++ API 参考
description: 从特定幻灯片开始添加新章节。
type: docs
weight: 14
url: /zh/aspose.slides/isectioncollection/addsection/
---
## ISectionCollection::AddSection(System::String, System::SharedPtr\<ISlide\>) 方法


添加从特定幻灯片开始的新章节。

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionCollection::AddSection(System::String name, System::SharedPtr<ISlide> startedFromSlide)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 章节的名称 |
| startedFromSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 章节的第一张幻灯片 |

### 返回值

已添加的章节。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISection](../../isection/)
* 类 [String](../../../system/string/)
* 类 [ISlide](../../islide/)
* 类 [ISectionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)