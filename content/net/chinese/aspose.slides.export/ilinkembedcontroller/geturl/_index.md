---
title: GetUrl
second_title: Aspose.Slides for .NET API 参考
description: 返回外部对象的 URL 如果String则始终调用此方法返回Link如果GetObjectStoringLocationaspose.slides.export/ilinkembedcontroller/getobjectstoringlocation返回Embed但嵌入是不可能的 可以为同一个对象 ID 多次调用
type: docs
weight: 20
url: /zh/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController.GetUrl method

返回外部对象的 URL。 如果String，则始终调用此方法)返回Link如果[`GetObjectStoringLocation`](../getobjectstoringlocation)返回Embed但嵌入是不可能的。 可以为同一个对象 ID 多次调用。

```csharp
public string GetUrl(int id, int referrer)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| id | Int32 | 对象 ID。此 id 保存操作范围的唯一性。 |
| referrer | Int32 | 引用对象的 id 或 0，如果对象被根文档引用。可用于生成相对链接。 |

### 返回值

外部对象的 URL 或 null 如果应忽略此对象。

### 也可以看看

* interface [ILinkEmbedController](../../ilinkembedcontroller)
* 命名空间 [Aspose.Slides.Export](../../ilinkembedcontroller)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
