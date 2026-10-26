---
title: Save
second_title: Aspose.Sildes for .NET API 참조
description: 문서 출력을 저장합니다.
type: docs
weight: 50
url: /ko/aspose.slides.export.web/webdocument/save/
---
## WebDocument.Save 메서드

문서 출력을 저장합니다.

```csharp
public void Save()
```

### 예제

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

    // "index-template.html" 템플릿을 "index" 템플릿 키와 함께 추가하여 나중에 사용합니다 (출력을 위해)
    document.Input.AddTemplate<Aspose.Slides.Presentation>("index", "index-template.html");

    // "index.html"을 출력 파일에 추가하고, "index" 템플릿을 사용해 생성하며 pres 변수를 모델로 사용합니다
    document.Output.Add("index.html", "index", pres);
    
    // ... 문서의 다른 옵션을 설정하고 문서를 저장합니다
    document.Global.Put("slideMargin", 10);
    document.Global.Put("imagesPath", "root/site/images");
    // ...
 
    document.Save();
}
```

### 관련 항목

* 클래스 [WebDocument](../../webdocument)
* 네임스페이스 [Aspose.Slides.Export.Web](../../webdocument)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: Aspose.Slides.dll용 xmldocmd에 의해 생성됨 -->