---
title: AsposeAIWebClient
second_title: Aspose.Slides cho Tham chiếu API Java
description: Một triển khai tích hợp sẵn kết nối tới LLM riêng của Aspose.
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

Một triển khai [IAIWebClient](../../com.aspose.slides/iaiwebclient) tích hợp sẵn kết nối tới LLM của riêng Aspose. Đây là client mặc định được sử dụng bởi constructor không tham số SlidesAIAgent().
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định bằng cách sử dụng HttpClient được quản lý bên ngoài. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Tạo một thể hiện của Aspose AI web client kết nối tới URL điểm cuối tùy chỉnh bằng cách sử dụng HttpClient được quản lý bên ngoài. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Tạo một phiên hội thoại. |
| [dispose()](#dispose--) | Giải phóng các tài nguyên được sử dụng bởi thể hiện này. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```


Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định. Đây là client được sử dụng bởi constructor không tham số SlidesAIAgent(), vì vậy việc tạo nó một cách rõ ràng chỉ cần thiết khi truyền client trực tiếp vào constructor SlidesAIAgent(IAIWebClient) trực tiếp.

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```


Tạo một thể hiện của Aspose AI web client kết nối tới điểm cuối Aspose LLM mặc định bằng cách sử dụng HttpClient được quản lý bên ngoài. HttpClient được cung cấp không bị giải phóng bởi thể hiện này và vẫn thuộc quyền sở hữu của người gọi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpClient được quản lý bên ngoài.

``` 
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```


Tạo một thể hiện của Aspose AI web client kết nối tới một URL điểm cuối tùy chỉnh. Sử dụng overload này khi bạn có URL do nhóm Aspose.Slides cung cấp; nếu không, hãy sử dụng overload AsposeAIWebClient() với URL mặc định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL điểm cuối của Aspose LLM, do nhóm Aspose.Slides cung cấp.

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```


Tạo một thể hiện của Aspose AI web client kết nối tới một URL điểm cuối tùy chỉnh bằng cách sử dụng HttpClient được quản lý bên ngoài. HttpClient được cung cấp không bị giải phóng bởi thể hiện này và vẫn thuộc quyền sở hữu của người gọi. Sử dụng overload này khi bạn có URL do nhóm Aspose.Slides cung cấp và muốn cung cấp HttpClient của mình; nếu bạn chỉ cần HttpClient của mình với URL mặc định, hãy sử dụng overload AsposeAIWebClient(HttpClient) thay thế.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL điểm cuối của Aspose LLM, do nhóm Aspose.Slides cung cấp. |
| httpClient | java.net.HttpURLConnection | Một thể hiện HttpClient được quản lý bên ngoài.

```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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


Gửi một chỉ thị chat tới mô hình AI bằng cách sử dụng một thể hiện HttpConnection được cung cấp và trả về tin nhắn phản hồi cho chỉ thị đã cho.

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


Tạo một phiên hội thoại. Khác với các cuộc gọi AI thông thường, các cuộc hội thoại giữ toàn bộ ngữ cảnh.

**Trả về:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Một [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Giải phóng các tài nguyên được sử dụng bởi thể hiện này.