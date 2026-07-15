---
title: OpenAIWebClient
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Client web OpenAI nhẹ tích hợp sẵn
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

Client web OpenAI nhẹ tích hợp sẵn
## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Tạo một thể hiện của client Web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của client Web OpenAI. |
## Phương thức

| Method | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Gửi một chỉ dẫn trò chuyện tới mô hình AI sử dụng một thể hiện được quản lý bên ngoài và trả về tin nhắn phản hồi cho chỉ dẫn đã cho. |
| [createConversation()](#createConversation--) | Tạo một thể hiện hội thoại. |
| [close()](#close--) | Giải phóng các tài nguyên được sử dụng bởi thể hiện này. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Tạo một thể hiện của client Web OpenAI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Giá trị có thể: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API OpenAI |
| organizationId | java.lang.String | ID tổ chức (tùy chọn) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Tạo một thể hiện của client Web OpenAI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Mô hình ngôn ngữ OpenAI. Giá trị có thể: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Khóa API OpenAI |
| organizationId | java.lang.String | ID tổ chức (tùy chọn) |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpURLConnection được quản lý bên ngoài. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Gửi một chỉ dẫn trò chuyện tới mô hình AI sử dụng một thể hiện được quản lý bên ngoài và trả về tin nhắn phản hồi cho chỉ dẫn đã cho.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | Chỉ dẫn hoặc tin nhắn sẽ được mô hình AI xử lý |

**Returns:**
java.lang.String - Tin nhắn được mô hình AI tạo ra để đáp lại chỉ dẫn đã cho.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tạo một thể hiện hội thoại. Khác với các cuộc gọi AI thông thường, hội thoại giữ lại toàn bộ ngữ cảnh.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một thể hiện [IAIConversation](../../com.aspose.slides/iaiconversation).

### close() {#close--}
```
public final void close()
```

Giải phóng các tài nguyên được sử dụng bởi thể hiện này.