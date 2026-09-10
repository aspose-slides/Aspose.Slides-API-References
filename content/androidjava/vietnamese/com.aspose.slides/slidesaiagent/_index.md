---
title: SlidesAIAgent
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tính năng dựa trên AI để xử lý bài thuyết trình.
type: docs
url: /vi/com.aspose.slides/slidesaiagent/
---
**Kế thừa:**
java.lang.Object
```
public class SlidesAIAgent
```

Cung cấp các tính năng dựa trên AI để xử lý bài thuyết trình.
## Phương thức khởi tạo

| Constructor | Description |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) với một client AI tuỳ chỉnh. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) bằng cách sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) được tích hợp sẵn với cấu hình mặc định của nó. |
## Phương thức

| Method | Description |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Dịch một bài thuyết trình sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Tạo một thể hiện bài thuyết trình từ mô tả văn bản. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Tạo một thể hiện bài thuyết trình từ mô tả văn bản. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) với một client AI tuỳ chỉnh. Sử dụng overload này để chỉ định nhà cung cấp AI, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection của riêng bạn). Bất kỳ triển khai nào của [IAIWebClient](../../com.aspose.slides/iaiwebclient) đều có thể được sử dụng. Để sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) được tích hợp sẵn với cấu hình mặc định, hãy dùng overload SlidesAIAgent() thay thế.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Thể hiện client AI. Bất kỳ triển khai nào của [IAIWebClient](../../com.aspose.slides/iaiwebclient) đều có thể được sử dụng. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) bằng cách sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) được tích hợp sẵn với cấu hình mặc định của nó. Client kết nối tới LLM của Aspose và không cần cấu hình bổ sung. Để sử dụng một client AI khác, hãy dùng overload SlidesAIAgent(IAIWebClient) thay thế.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Dịch một bài thuyết trình sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bài thuyết trình mục tiêu |
| language | java.lang.String | Ngôn ngữ mục tiêu

--------------------

Ví dụ dưới đây sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) mặc định, được tạo bởi hàm khởi tạo SlidesAIAgent() không tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection của riêng bạn), hãy truyền một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) cho hàm khởi tạo SlidesAIAgent(IAIWebClient).

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

Tạo một thể hiện bài thuyết trình từ mô tả văn bản. Cung cấp chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn. |
| presentationContentAmount | int | Số lượng nội dung trong bài thuyết trình được tạo ra. |

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

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Tạo một thể hiện bài thuyết trình từ mô tả văn bản. Cung cấp chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn bằng ngôn ngữ yêu cầu.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản ngắn. |
| presentationContentAmount | int | Số lượng nội dung trong bài thuyết trình được tạo ra. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Một bài thuyết trình được dùng làm mẫu cho bố cục và thiết kế, thay thế mẫu mặc định.

--------------------

Ví dụ dưới đây sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) mặc định, được tạo bởi hàm khởi tạo SlidesAIAgent() không tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM của riêng bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection của riêng bạn), hãy truyền một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) cho hàm khởi tạo SlidesAIAgent(IAIWebClient).

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

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)