---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将 WebVTT 闭合字幕添加到集合的末尾。
type: docs
weight: 27
url: /zh/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) 方法

将 WebVTT 闭合字幕添加到集合的末尾。

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 闭合字幕的标签。 |
| filePath | [System::String](../../../system/string/) | WebVTT 文件的路径。 |

### 返回值

添加的 [ICaptions](../../icaptions/) 实例。

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) 方法

从流中将 WebVTT 闭合字幕添加到集合的末尾。

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 闭合字幕的标签。 |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含 WebVTT 格式数据的输入流。 |

### 返回值

添加的 [ICaptions](../../icaptions/) 实例。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICaptions](../../icaptions/)
* 类 [String](../../../system/string/)
* 类 [CaptionsCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)