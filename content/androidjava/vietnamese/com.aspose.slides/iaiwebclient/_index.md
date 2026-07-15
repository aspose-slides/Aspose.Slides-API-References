---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /vi/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Giao diện AI Web client. Giao diện này cho phép thay thế các mô hình ngôn ngữ AI khác nhau. Các lớp triển khai giao diện này được sử dụng cùng với SlidesAIAgent.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Gửi một chỉ thị trò chuyện tới mô hình AI bằng cách sử dụng một thể hiện HttpConnection đã cung cấp và trả về tin nhắn phản hồi cho chỉ thị đã cho. |
| [createConversation()](#createConversation--) | Tạo một thể hiện cuộc trò chuyện. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Gửi một chỉ thị trò chuyện tới mô hình AI bằng cách sử dụng một thể hiện HttpConnection đã cung cấp và trả về tin nhắn phản hồi cho chỉ thị đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String | Chỉ thị hoặc tin nhắn sẽ được mô hình AI xử lý. |

**Giá trị trả về:**
java.lang.String - Tin nhắn được mô hình AI tạo ra để đáp lại chỉ thị đã cho.
### createConversation() {#createConversation--}
```
public abstract IIAConversation createConversation()
```


Tạo một thể hiện cuộc trò chuyện. Khác với các cuộc gọi AI thông thường, các cuộc trò chuyện giữ lại toàn bộ ngữ cảnh.

**Giá trị trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một [IAIConversation](../../com.aspose.slides/iaiconversation) thể hiện.