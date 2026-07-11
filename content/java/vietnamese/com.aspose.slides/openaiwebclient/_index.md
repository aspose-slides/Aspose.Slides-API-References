---
title: OpenAIWebClient
second_title: Tham chiếu API Aspose.Slides cho Java
description: Một triển khai tích hợp sẵn kết nối tới API OpenAI.
type: docs
url: /vi/com.aspose.slides/openaiwebclient/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn kết nối tới API OpenAI.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tạo một đối tượng của OpenAI web client. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tạo một đối tượng của OpenAI web client sử dụng HttpClient được quản lý bên ngoài. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tạo một phiên trò chuyện. |
| [close()](#close--) | Giải phóng tài nguyên được sử dụng bởi đối tượng này. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Tạo một đối tượng của OpenAI web client.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Các giá trị khả dụng: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API của OpenAI. |
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

Tạo một đối tượng của OpenAI web client sử dụng một HttpClient được quản lý bên ngoài. HttpClient được cung cấp sẽ không bị giải phóng bởi đối tượng này và vẫn do người gọi sở hữu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Các giá trị khả dụng: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API của OpenAI |
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

Gửi một chỉ thị trò chuyện tới mô hình AI bằng một thể hiện HttpConnection được cung cấp và trả về tin nhắn phản hồi cho chỉ thị đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String |  |
**Trả về:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Tạo một phiên trò chuyện. Khác với các lời gọi AI thông thường, các cuộc trò chuyện giữ lại toàn bộ ngữ cảnh.

**Trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một [IAIConversation](../../com.aspose.slides/iaiconversation) thể hiện.
### close() {#close--}
```
public final void close()
```

Giải phóng tài nguyên được sử dụng bởi đối tượng này.