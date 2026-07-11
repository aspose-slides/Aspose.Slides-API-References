---
title: OpenAICompatibleWebClient
second_title: Tham chiếu API Aspose.Slides cho Java
description: Một triển khai tích hợp sẵn kết nối tới nhà cung cấp LLM tương thích OpenAI tại URL cơ sở được chỉ định.
type: docs
url: /vi/com.aspose.slides/openaicompatiblewebclient/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn, kết nối tới nhà cung cấp LLM tương thích OpenAI tại URL cơ sở được chỉ định.  

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tạo một thể hiện của client web tương thích OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của client web tương thích OpenAI sử dụng HttpClient được quản lý bên ngoài. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tạo một thể hiện hội thoại. |
| [dispose()](#dispose--) | Giải phóng tài nguyên được sử dụng bởi thể hiện này. |
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
| baseUrl | java.lang.String | URL cơ sở của LLM tương thích OpenAI.

```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

Tạo một thể hiện của client web tương thích OpenAI sử dụng HttpClient được quản lý bên ngoài. HttpClient được cung cấp không được giải phóng bởi thể hiện này và vẫn thuộc sở hữu của người gọi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Tên mô hình được nhà cung cấp LLM hỗ trợ. |
| apiKey | java.lang.String | Khóa API (token). |
| baseUrl | java.lang.String | URL cơ sở của LLM tương thích OpenAI. |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpClient được quản lý bên ngoài.

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Gửi một chỉ thị trò chuyện tới mô hình AI bằng một thể hiện HttpConnection được cung cấp và trả về tin nhắn phản hồi cho chỉ thị đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Trả về:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tạo một thể hiện hội thoại. Khác với các lời gọi AI thông thường, các hội thoại giữ lại toàn bộ ngữ cảnh.

**Trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một thể hiện [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng tài nguyên được sử dụng bởi thể hiện này.