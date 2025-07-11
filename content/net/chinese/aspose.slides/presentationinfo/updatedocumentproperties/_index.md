---
title: UpdateDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: 更新绑定演示文稿的属性。
type: docs
weight: 80
url: /zh/aspose.slides/presentationinfo/updatedocumentproperties/
---

## PresentationInfo.UpdateDocumentProperties 方法

更新绑定演示文稿的属性。

```csharp
public void UpdateDocumentProperties(IDocumentProperties documentProperties)
```

### 示例

此示例显示如何调用 `UpdateDocumentProperties` 方法以更新通过调用 [`ReadDocumentProperties`](../readdocumentproperties) 方法返回的文档属性。

```csharp
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Subject = "New subject";
props.LastSavedTime = DateTime.UtcNow;
info.UpdateDocumentProperties(props);
info.WriteBindedPresentation("new_pres.pptx");
```

### 另请参见

* 接口 [IDocumentProperties](../../idocumentproperties)
* 类 [PresentationInfo](../../presentationinfo)
* 命名空间 [Aspose.Slides](../../presentationinfo)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->