---
title: GetUrl()
second_title: Aspose.Slides for C++ API 参考
description: "返回指向外部对象的 URL。如果 ILinkEmbedController::GetObjectStoringLocation 返回 LinkEmbedDecision::Link，则始终调用此方法；如果 ILinkEmbedController::GetObjectStoringLocation 返回 LinkEmbedDecision::Embed，但嵌入不可行，则可能调用此方法。对同一对象 id 可多次调用。"
type: docs
weight: 14
url: /zh/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) 方法

返回指向外部对象的 URL。如果 [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) 返回 [LinkEmbedDecision::Link](../../linkembeddecision/)，则始终调用此方法；如果 [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) 返回 [LinkEmbedDecision::Embed](../../linkembeddecision/)，则可能调用此方法，但嵌入是不可行的。对同一对象 id 可以多次调用。

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | **int32_t** | 对象 id。此 id 在整个操作期间唯一。 |
| referrer | **int32_t** | 引用对象的 id，若对象由根文档引用则为 0。可能用于生成相对链接。 |

### 返回值

外部对象的 Url，若该对象应被忽略则为 null。

## 另见

* 类 [String](../../../system/string/)
* 类 [ILinkEmbedController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)