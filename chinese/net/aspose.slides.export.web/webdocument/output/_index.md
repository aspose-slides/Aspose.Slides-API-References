---
title: Output
second_title: Aspose.Slides for .NET API 参考
description: 返回文档输出元素的集合 只读Outputaspose.slides.export.web/webdocument/output
type: docs
weight: 40
url: /zh/net/aspose.slides.export.web/webdocument/output/
---
## WebDocument.Output property

返回文档输出元素的集合。 只读`Output`。

```csharp
public Output Output { get; }
```

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    var options = new WebDocumentOptions
    {
        TemplateEngine = new RazorTemplateEngine(),
        OutputSaver = new FileOutputSaver(),
        EmbedImages = false
    };
    
    WebDocument document = new WebDocument(options);

     // 将“index.html”添加到输出文件中，使用“index”模板生成它并将变量作为model
    document.Output.Add("index.html", "index", pres);

     // ... 设置文档的其他选项，然后保存文档
    document.Save();
}
```

### 也可以看看

* class [Output](../../output)
* class [WebDocument](../../webdocument)
* 命名空间 [Aspose.Slides.Export.Web](../../webdocument)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->