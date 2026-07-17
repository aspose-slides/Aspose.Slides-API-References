---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API 参考
description: 将幻灯片内容保存为 EMF 文件。
type: docs
weight: 170
url: /zh/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 方法

将幻灯片内容保存为 EMF 文件。

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目标流 |

## 备注

以下代码示例演示了如何将 PowerPoint 演示文稿的第一张幻灯片转换为元文件。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// 将第一张幻灯片保存为元文件
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [Slide](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)