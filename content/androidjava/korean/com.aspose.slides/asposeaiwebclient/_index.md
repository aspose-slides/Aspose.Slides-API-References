---
title: AsposeAIWebClient
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
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

Aspose 고유의 LLM에 연결하는 내장 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현입니다. 매개변수 없이 호출하는 SlidesAIAgent() 생성자가 사용하는 기본 클라이언트입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpURLConnection을 사용하여 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpURLConnection을 사용하여 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | AI 모델에 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다. |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [dispose()](#dispose--) | 이 인스턴스가 사용하는 리소스를 해제합니다. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 이 클라이언트는 매개변수 없이 호출하는 SlidesAIAgent() 생성자가 사용하므로, 클라이언트를 직접 SlidesAIAgent(IAIWebClient) 생성자에 전달하려는 경우에만 명시적으로 생성하면 됩니다.

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

외부에서 관리되는 HttpURLConnection을 사용하여 기본 Aspose LLM 엔드포인트에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 제공된 HttpURLConnection은 이 인스턴스에서 해제되지 않으며 호출자에게 소유권이 계속 유지됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpURLConnection 인스턴스.

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

사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. Aspose.Slides 팀에서 제공한 URL이 있는 경우에 이 오버로드를 사용하고, 그렇지 않다면 기본 URL을 사용하는 AsposeAIWebClient() 오버로드를 사용하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides 팀에서 제공한 Aspose LLM의 엔드포인트 URL.

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

외부에서 관리되는 HttpURLConnection을 사용하여 사용자 지정 엔드포인트 URL에 연결하는 Aspose AI 웹 클라이언트 인스턴스를 생성합니다. 제공된 HttpURLConnection은 이 인스턴스에서 해제되지 않으며 호출자에게 소유권이 계속 유지됩니다. Aspose.Slides 팀에서 제공한 URL과 자체 HttpURLConnection을 모두 사용하려는 경우 이 오버로드를 사용하고, 기본 URL과 자체 HttpURLConnection만 필요한 경우에는 AsposeAIWebClient(HttpURLConnection) 오버로드를 사용하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.lang.String | Aspose.Slides 팀에서 제공한 Aspose LLM의 엔드포인트 URL. |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpURLConnection 인스턴스.

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

AI 모델에 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String | AI 모델이 처리할 명령 또는 메시지.

**반환값:**
java.lang.String - 주어진 명령에 대한 AI 모델이 생성한 메시지.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

대화 인스턴스를 생성합니다. 일반 AI 호출과 달리, 대화는 전체 컨텍스트를 유지합니다.

**반환값:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) 인스턴스.
### dispose() {#dispose--}
```
public final void dispose()
```

이 인스턴스가 사용하는 리소스를 해제합니다.