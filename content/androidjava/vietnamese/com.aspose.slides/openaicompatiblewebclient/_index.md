---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Một triển khai tích hợp sẵn kết nối tới nhà cung cấp LLM tương thích OpenAI tại URL cơ sở được chỉ định.
type: docs
url: /vi/com.aspose.slides/openaicompatiblewebclient/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn kết nối tới nhà cung cấp LLM tương thích OpenAI tại URL cơ sở được chỉ định.
## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tạo một thể hiện của client web tương thích OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của client web tương thích OpenAI sử dụng một HttpURLConnection được quản lý bên ngoài. |
## Các phương thức

| Method | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Gửi một chỉ thị trò chuyện tới mô hình AI bằng một HttpURLConnection được quản lý bên ngoài và trả về tin nhắn phản hồi cho chỉ thị đã cho. |
| [createConversation()](#createConversation--) | Tạo một thể hiện cuộc trò chuyện. |
| [dispose()](#dispose--) | Giải phóng các tài nguyên được thể hiện này sử dụng. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```


Tạo một thể hiện của client web tương thích OpenAI.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Tên mô hình được nhà cung cấp LLM hỗ trợ. |
| apiKey | java.lang.String | Khóa API (token). |
| baseUrl | java.lang.String | URL cơ sở của LLM tương thích OpenAI. |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```


Tạo một thể hiện của client web tương thích OpenAI sử dụng một HttpURLConnection được quản lý bên ngoài. HttpURLConnection được cung cấp sẽ không được giải phóng bởi thể hiện này và vẫn thuộc sở hữu của người gọi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Tên mô hình được nhà cung cấp LLM hỗ trợ. |
| apiKey | java.lang.String | Khóa API (token). |
| baseUrl | java.lang.String | URL cơ sở của LLM tương thích OpenAI. |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpURLConnection được quản lý bên ngoài. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Gửi một chỉ thị trò chuyện tới mô hình AI bằng một HttpURLConnection được quản lý bên ngoài và trả về tin nhắn phản hồi cho chỉ thị đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String | Chỉ thị hoặc tin nhắn sẽ được mô hình AI xử lý. |

**Trả về:**
java.lang.String - Tin nhắn do mô hình AI tạo ra để đáp lại chỉ thị đã cho.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Tạo một thể hiện cuộc trò chuyện. Không giống như các cuộc gọi AI thông thường, cuộc trò chuyện giữ lại toàn bộ ngữ cảnh.

**Trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một thể hiện [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```


Giải phóng các tài nguyên được thể hiện này sử dụng.