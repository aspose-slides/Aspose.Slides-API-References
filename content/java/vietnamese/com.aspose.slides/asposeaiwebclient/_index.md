---
title: AsposeAIWebClient
second_title: Aspose.Slides cho Tham chiếu API Java
description: Một triển khai tích hợp sẵn kết nối đến LLM của Aspose.
type: docs
url: /vi/com.aspose.slides/asposeaiwebclient/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn kết nối đến LLM của Aspose. Đây là client mặc định được sử dụng bởi hàm khởi tạo không tham số  SlidesAIAgent()  .

## Phương thức khởi tạo

| Phương thức khởi tạo | Mô tả |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định bằng cách sử dụng HttpURLConnection được quản lý bên ngoài. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh bằng cách sử dụng HttpURLConnection được quản lý bên ngoài. |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Gửi một chỉ dẫn trò chuyện tới mô hình AI và trả về tin nhắn phản hồi cho chỉ dẫn đã cho. |
| [createConversation()](#createConversation--) | Tạo một thể hiện hội thoại. |
| [dispose()](#dispose--) | Giải phóng các tài nguyên được sử dụng bởi thể hiện này. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định. Đây là client được sử dụng bởi hàm khởi tạo không tham số  SlidesAIAgent() , vì vậy việc tạo nó một cách rõ ràng chỉ cần thiết khi truyền client trực tiếp vào hàm khởi tạo  SlidesAIAgent(IAIWebClient) .

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định bằng cách sử dụng HttpURLConnection được quản lý bên ngoài. HttpURLConnection được cung cấp không bị giải phóng bởi thể hiện này và vẫn thuộc sở hữu của người gọi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpURLConnection được quản lý bên ngoài. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh. Hãy sử dụng overload này khi bạn có URL do nhóm Aspose.Slides cung cấp; nếu không, sử dụng overload  AsposeAIWebClient()  với URL mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL điểm cuối của Aspose LLM, do nhóm Aspose.Slides cung cấp. |

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh bằng cách sử dụng HttpURLConnection được quản lý bên ngoài. HttpURLConnection được cung cấp không bị giải phóng bởi thể hiện này và vẫn thuộc sở hữu của người gọi. Sử dụng overload này khi bạn có URL do nhóm Aspose.Slides cung cấp và muốn cung cấp HttpURLConnection của riêng mình; nếu bạn chỉ cần HttpURLConnection của riêng mình với URL mặc định, hãy sử dụng overload  AsposeAIWebClient(HttpURLConnection)  thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL điểm cuối của Aspose LLM, do nhóm Aspose.Slides cung cấp. |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpURLConnection được quản lý bên ngoài. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

Gửi một chỉ dẫn trò chuyện tới mô hình AI và trả về tin nhắn phản hồi cho chỉ dẫn đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| instruction | java.lang.String | Chỉ dẫn hoặc tin nhắn sẽ được mô hình AI xử lý. |

**Trả về:**
java.lang.String - Tin nhắn được mô hình AI tạo ra để đáp lại chỉ dẫn đã cho.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Tạo một thể hiện hội thoại. Không giống như các cuộc gọi AI thông thường, các hội thoại giữ lại toàn bộ ngữ cảnh.

**Trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng các tài nguyên được sử dụng bởi thể hiện này.