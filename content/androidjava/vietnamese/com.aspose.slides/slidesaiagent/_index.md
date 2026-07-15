---
title: SlidesAIAgent
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tính năng được hỗ trợ bởi AI để xử lý bản trình bày.
type: docs
url: /vi/com.aspose.slides/slidesaiagent/
---
**Kế thừa:**
java.lang.Object
```
public class SlidesAIAgent
```

Cung cấp các tính năng được hỗ trợ bởi AI để xử lý bản trình bày.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent hàm tạo |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Dịch một bản trình bày sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Tạo một thể hiện bản trình bày từ mô tả văn bản. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Tạo một thể hiện bản trình bày từ mô tả văn bản. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent hàm tạo

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | đối tượng khách hàng AI |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

Dịch một bản trình bày sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày mục tiêu |
| language | java.lang.String | Ngôn ngữ mục tiêu

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

Tạo một thể hiện bản trình bày từ mô tả văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản bằng ngôn ngữ yêu cầu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản. |
| presentationContentAmount | int | Số lượng nội dung trong bản trình bày kết quả.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Tạo một thể hiện bản trình bày từ mô tả văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản bằng ngôn ngữ yêu cầu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản. |
| presentationContentAmount | int | Số lượng nội dung trong bản trình bày kết quả. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Một bản trình bày được dùng làm mẫu cho bố cục và thiết kế, thay thế mẫu mặc định.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)