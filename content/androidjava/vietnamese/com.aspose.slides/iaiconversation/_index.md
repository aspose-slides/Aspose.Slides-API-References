---
title: IAIConversation
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một thực thể cuộc trò chuyện.
type: docs
url: /vi/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Đại diện cho một thực thể cuộc trò chuyện. Khác với các cuộc gọi AI thông thường, các cuộc trò chuyện giữ lại toàn bộ ngữ cảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Sends conversation request message including entire context and returns response. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Gửi tin nhắn yêu cầu cuộc trò chuyện bao gồm toàn bộ ngữ cảnh và trả về phản hồi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String | Lệnh hoặc tin nhắn sẽ được mô hình AI xử lý. |

**Trả về:**
java.lang.String - Tin nhắn do mô hình AI tạo ra để đáp lại lệnh đã cho trong ngữ cảnh cuộc trò chuyện.