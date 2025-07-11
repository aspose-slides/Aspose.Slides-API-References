---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: 将 WebVTT 关闭字幕添加到集合的末尾。
type: docs
weight: 30
url: /zh/aspose.slides/icaptionscollection/add/
---

## Add(string, string) {#add_1}

将 WebVTT 关闭字幕添加到集合的末尾。

```csharp
public ICaptions Add(string label, string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | String | 关闭字幕的标签。 |
| filePath | String | WebVTT 文件的路径。 |

### 返回值

添加的 [`ICaptions`](../../icaptions) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 *filePath* 为 `null`，则抛出。 |
| ArgumentException | 如果 *filePath* 为空，则抛出。 |

### 另请参见

* 接口 [ICaptions](../../icaptions)
* 接口 [ICaptionsCollection](../../icaptionscollection)
* 命名空间 [Aspose.Slides](../../icaptionscollection)
* 程序集 [Aspose.Slides](../../../)

---

## Add(string, Stream) {#add}

从流中将 WebVTT 关闭字幕添加到集合的末尾。

```csharp
public ICaptions Add(string label, Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | String | 关闭字幕的标签。 |
| stream | Stream | 包含 WebVTT 格式数据的输入流。 |

### 返回值

添加的 [`ICaptions`](../../icaptions) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 *stream* 为 `null`，则抛出。 |
| ArgumentException | 如果输入数据不是 WebVTT 格式，则抛出。 |

### 另请参见

* 接口 [ICaptions](../../icaptions)
* 接口 [ICaptionsCollection](../../icaptionscollection)
* 命名空间 [Aspose.Slides](../../icaptionscollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->