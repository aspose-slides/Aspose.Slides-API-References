---
title: OpenAIWebClient
second_title: Tham chiếu API Aspose.Slides cho Java
description: Một triển khai tích hợp sẵn kết nối tới API OpenAI.
type: docs
url: /vi/com.aspose.slides/openaiwebclient/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn kết nối tới API OpenAI.

## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tạo một thể hiện của client web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của client web OpenAI sử dụng HttpClient được quản lý bên ngoài. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tạo một thể hiện hội thoại. |
| [close()](#close--) | Giải phóng các tài nguyên được sử dụng bởi thể hiện này. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Tạo một thể hiện của client web OpenAI.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Các giá trị có thể: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API OpenAI. |
| organizationId | java.lang.String | ID tổ chức (tùy chọn). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Tạo một thể hiện của client web OpenAI sử dụng HttpClient được quản lý bên ngoài. HttpClient được cung cấp không bị giải phóng bởi thể hiện này và vẫn thuộc sở hữu của người gọi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Các giá trị có thể: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API OpenAI |
| organizationId | java.lang.String | ID tổ chức (tùy chọn) |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpClient được quản lý bên ngoài |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

Gửi một chỉ thị trò chuyện tới mô hình AI bằng một thể hiện HttpConnection được cung cấp và trả về thông báo phản hồi cho chỉ thị đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Giá trị trả về:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tạo một thể hiện hội thoại. Không giống các lời gọi AI thông thường, hội thoại giữ lại toàn bộ ngữ cảnh.

**Giá trị trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một thể hiện [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Giải phóng các tài nguyên được sử dụng bởi thể hiện này.