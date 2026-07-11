---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides for Java API 레퍼런스
description: 지정된 기본 URL에서 OpenAI 호환 LLM 제공자에 연결하는 내장 구현입니다.
type: docs
url: /ko/com.aspose.slides/openaicompatiblewebclient/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

지정된 기본 URL에서 OpenAI 호환 LLM 제공자에 연결하는 내장 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI 호환 웹 클라이언트 인스턴스를 생성합니다. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpClient를 사용하는 OpenAI 호환 웹 클라이언트 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [dispose()](#dispose--) | 이 인스턴스에서 사용된 리소스를 해제합니다. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

OpenAI 호환 웹 클라이언트 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | LLM 제공자가 지원하는 모델 이름입니다. |
| apiKey | java.lang.String | API 키(토큰)입니다. |
| baseUrl | java.lang.String | OpenAI 호환 LLM의 기본 URL입니다. |
```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

외부에서 관리되는 HttpClient를 사용하는 OpenAI 호환 웹 클라이언트 인스턴스를 생성합니다. 제공된 HttpClient는 이 인스턴스에 의해 해제되지 않으며 호출자에 의해 소유됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | LLM 제공자가 지원하는 모델 이름입니다. |
| apiKey | java.lang.String | API 키(토큰)입니다. |
| baseUrl | java.lang.String | OpenAI 호환 LLM의 기본 URL입니다. |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpClient 인스턴스입니다. |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
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

제공된 HttpConnection 인스턴스를 사용하여 AI 모델에 채팅 지시를 전송하고 해당 지시의 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String |  |

**반환값:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

대화 인스턴스를 생성합니다. 일반 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다.

**반환값:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

이 인스턴스에서 사용된 리소스를 해제합니다.