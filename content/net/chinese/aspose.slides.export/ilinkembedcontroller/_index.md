---
title: ILinkEmbedController
second_title: Aspose.Slides for .NET API 参考
description: 回调接口用于确定在保存期间应如何处理对象
type: docs
weight: 3660
url: /zh/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController interface

回调接口，用于确定在保存期间应如何处理对象。

```csharp
public interface ILinkEmbedController
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetObjectStoringLocation](../../aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation)(int, byte[], string, string, string) | 确定对象的存储位置。 对每个对象 ID 调用一次此方法。 不能保证不会有两个对象具有相同的数据，semanticName 和 contentType 但具有不同的 id。 |
| [GetUrl](../../aspose.slides.export/ilinkembedcontroller/geturl)(int, int) | 返回外部对象的 URL。 如果String，则始终调用此方法)返回Link如果[`GetObjectStoringLocation`](./getobjectstoringlocation)返回Embed但嵌入是不可能的。 可以为同一个对象 ID 多次调用。 |
| [SaveExternal](../../aspose.slides.export/ilinkembedcontroller/saveexternal)(int, byte[]) | 保存外部对象。 |

### 也可以看看

* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
