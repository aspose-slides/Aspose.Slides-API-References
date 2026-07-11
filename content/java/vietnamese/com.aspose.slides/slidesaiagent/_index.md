---
title: SlidesAIAgent
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các tính năng dựa trên AI để xử lý bản trình bày.
type: docs
url: /vi/com.aspose.slides/slidesaiagent/
---
**Kế thừa:**
java.lang.Object
```
public class SlidesAIAgent
```

Cung cấp các tính năng dựa trên AI để xử lý bản trình bày.

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) với một khách hàng AI tùy chỉnh. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) bằng cách sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định của nó. |

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

Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) với một khách hàng AI tùy chỉnh. Sử dụng phiên bản này để chỉ định nhà cung cấp AI, cung cấp LLM riêng của bạn, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection riêng). Bất kỳ triển khai nào của [IAIWebClient](../../com.aspose.slides/iaiwebclient) đều có thể được sử dụng. Để sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định, hãy sử dụng phiên bản SlidesAIAgent() thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Thực thể khách hàng AI. Bất kỳ triển khai nào của [IAIWebClient](../../com.aspose.slides/iaiwebclient) đều có thể được sử dụng. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Khởi tạo một thể hiện mới của [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) bằng cách sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) tích hợp sẵn với cấu hình mặc định của nó. Khách hàng kết nối tới LLM của Aspose và không yêu cầu cấu hình bổ sung. Để sử dụng một khách hàng AI khác, hãy sử dụng phiên bản SlidesAIAgent(IAIWebClient) thay thế.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Dịch một bản trình bày sang ngôn ngữ được chỉ định bằng AI (phiên bản đồng bộ).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày mục tiêu |
| language | java.lang.String | Ngôn ngữ mục tiêu |

--------------------

Ví dụ dưới đây sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) mặc định, được tạo bởi hàm khởi tạo SlidesAIAgent() không tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM riêng, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection riêng), truyền một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) vào hàm khởi tạo SlidesAIAgent(IAIWebClient).

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

Tạo một thể hiện bản trình bày từ mô tả văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản trong ngôn ngữ yêu cầu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản. |
| presentationContentAmount | int | Lượng nội dung trong bản trình bày kết quả.

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

Tạo một thể hiện bản trình bày từ mô tả văn bản. Cung cấp một chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản trong ngôn ngữ yêu cầu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| description | java.lang.String | Chủ đề, ý tưởng, trích dẫn hoặc đoạn văn bản. |
| presentationContentAmount | int | Lượng nội dung trong bản trình bày kết quả. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Một bản trình bày để dùng làm mẫu cho bố cục và thiết kế, thay thế mẫu mặc định.

--------------------

Ví dụ dưới đây sử dụng [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) mặc định, được tạo bởi hàm khởi tạo SlidesAIAgent() không tham số và kết nối tới LLM của Aspose. Để sử dụng nhà cung cấp AI khác, cung cấp LLM riêng, hoặc tùy chỉnh kết nối (ví dụ, bằng cách cung cấp java.net.HttpURLConnection riêng), truyền một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) vào hàm khởi tạo SlidesAIAgent(IAIWebClient).

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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