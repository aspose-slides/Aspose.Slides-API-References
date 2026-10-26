---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Giao diện máy khách AI Web.
type: docs
url: /vi/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Giao diện máy khách AI Web. Giao diện này cho phép thay thế các mô hình ngôn ngữ AI khác nhau. Các lớp triển khai giao diện này dự kiến sẽ được sử dụng cùng với SlidesAIAgent.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Gửi một lệnh trò chuyện tới mô hình AI bằng một thể hiện HttpConnection được cung cấp và trả về tin nhắn phản hồi cho lệnh đã cho. |
| [createConversation()](#createConversation--) | Tạo một thể hiện cuộc trò chuyện. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Gửi một lệnh trò chuyện tới mô hình AI bằng một thể hiện HttpConnection được cung cấp và trả về tin nhắn phản hồi cho lệnh đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String | Lệnh hoặc tin nhắn sẽ được mô hình AI xử lý. |

**Giá trị trả về:**
java.lang.String - Tin nhắn được mô hình AI tạo ra để đáp lại lệnh đã cho.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Tạo một thể hiện cuộc trò chuyện. Không giống các cuộc gọi AI thông thường, các cuộc trò chuyện giữ lại toàn bộ ngữ cảnh.

**Giá trị trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một thể hiện [IAIConversation](../../com.aspose.slides/iaiconversation).