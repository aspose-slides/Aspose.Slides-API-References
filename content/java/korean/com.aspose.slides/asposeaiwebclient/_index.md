---
title: AsposeAIWebClient
second_title: Aspose.Slides용 Java API 레퍼런스
description: Aspose 고유의 LLM에 연결하는 내장 구현입니다.
type: docs
url: /ko/com.aspose.slides/asposeaiwebclient/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Aspose 고유의 LLM에 연결하는 내장 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현입니다. 이는 매개변수 없이 SlidesAIAgent() 생성자를 사용할 때 기본 클라이언트입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpClient 를 사용하여 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpClient 를 사용하여 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [dispose()](#dispose--) | 이 인스턴스가 사용한 리소스를 해제합니다. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 이는 매개변수 없이 SlidesAIAgent() 생성자를 사용할 때 사용되는 클라이언트이므로, 클라이언트를 SlidesAIAgent(IAIWebClient) 생성자에 직접 전달하려는 경우에만 명시적으로 생성하면 됩니다.

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

외부에서 관리되는 HttpClient 를 사용하여 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 제공된 HttpClient 는 이 인스턴스에 의해 해제되지 않으며 호출자에게 소유가 남아 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpClient 인스턴스.

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

사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. Aspose.Slides 팀이 제공한 URL이 있는 경우 이 오버로드를 사용하고, 그렇지 않으면 기본 URL이 포함된 AsposeAIWebClient() 오버로드를 사용하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides 팀이 제공한 Aspose LLM의 엔드포인트 URL.

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

외부에서 관리되는 HttpClient 를 사용하여 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 제공된 HttpClient 는 이 인스턴스에 의해 해제되지 않으며 호출자에게 소유가 남아 있습니다. Aspose.Slides 팀이 제공한 URL이 있고 자체 HttpClient 를 제공하려는 경우 이 오버로드를 사용하십시오; 기본 URL에 자체 HttpClient 만 필요하면 AsposeAIWebClient(HttpClient) 오버로드를 사용하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides 팀이 제공한 Aspose LLM의 엔드포인트 URL. |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpClient 인스턴스.

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

제공된 HttpConnection 인스턴스를 사용하여 AI 모델에 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String |  |

**반환값:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

대화 인스턴스를 생성합니다. 일반적인 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다.

**반환값:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### dispose() {#dispose--}
```
public final void dispose()
```

이 인스턴스가 사용한 리소스를 해제합니다.