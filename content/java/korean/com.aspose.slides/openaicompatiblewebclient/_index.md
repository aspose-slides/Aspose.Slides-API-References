---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API 레퍼런스
description: 지정된 기본 URL에서 OpenAI 호환 LLM 공급자에 연결하는 내장 구현입니다.
type: docs
url: /ko/com.aspose.slides/openaicompatiblewebclient/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

지정된 기본 URL에서 OpenAI 호환 LLM 공급자에 연결하는 내장된 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI 호환 웹 클라이언트의 인스턴스를 생성합니다. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpURLConnection을 사용하는 OpenAI 호환 웹 클라이언트의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 외부에서 관리되는 HttpURLConnection 인스턴스를 사용하여 AI 모델에 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다. |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [dispose()](#dispose--) | 이 인스턴스가 사용한 리소스를 해제합니다. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI 호환 웹 클라이언트의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | LLM 공급자가 지원하는 모델 이름입니다. |
| apiKey | java.lang.String | API 키(토큰)입니다. |
| baseUrl | java.lang.String | OpenAI 호환 LLM의 기본 URL입니다. |

```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
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
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

외부에서 관리되는 HttpURLConnection을 사용하는 OpenAI 호환 웹 클라이언트의 인스턴스를 생성합니다. 제공된 HttpURLConnection은 이 인스턴스에 의해 해제되지 않으며 호출자에 의해 소유됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | LLM 공급자가 지원하는 모델 이름입니다. |
| apiKey | java.lang.String | API 키(토큰)입니다. |
| baseUrl | java.lang.String | OpenAI 호환 LLM의 기본 URL입니다. |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpURLConnection 인스턴스입니다. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

외부에서 관리되는 HttpURLConnection 인스턴스를 사용하여 AI 모델에 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String | AI 모델이 처리할 명령 또는 메시지입니다. |

**반환값:**  
java.lang.String - 주어진 명령에 대한 AI 모델이 생성한 메시지입니다.
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

대화 인스턴스를 생성합니다. 일반 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다.

**반환값:**  
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) 인스턴스.
### dispose() {#dispose--}
```
public final void dispose()
```

이 인스턴스가 사용한 리소스를 해제합니다.