---
title: FoundResult()
second_title: Aspose.Slides for C++ API 参考
description: 接收已查找文本数据的回调方法。
type: docs
weight: 1
url: /zh/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) 方法

接收已查找文本数据的回调方法。

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | 在其中找到文本的 [ITextFrame](../../itextframe/)。 |
| sourceText | [System::String](../../../system/string/) | 在其中找到文本的源文本。 |
| foundText | [System::String](../../../system/string/) | 找到的文本。 |
| textPosition | **int32_t** | 已找到文本的位置。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITextFrame](../../itextframe/)
* 类 [String](../../../system/string/)
* 类 [IFindResultCallback](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)