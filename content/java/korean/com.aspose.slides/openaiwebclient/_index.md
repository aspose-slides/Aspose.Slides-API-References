---
title: OpenAIWebClient
second_title: Aspose.Slides for Java API 레퍼런스
description: OpenAI API에 연결하는 내장 구현입니다.
type: docs
url: /ko/com.aspose.slides/openaiwebclient/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

OpenAI API에 연결하는 내장 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI 웹 클라이언트의 인스턴스를 생성합니다. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | 외부에서 관리되는 HttpClient 를 사용하는 OpenAI 웹 클라이언트의 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [close()](#close--) | 이 인스턴스에서 사용된 리소스를 해제합니다. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

OpenAI 웹 클라이언트의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 언어 모델. 가능한 값: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 키. |
| organizationId | java.lang.String | 조직 ID (옵션). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

외부에서 관리되는 HttpClient 를 사용하는 OpenAI 웹 클라이언트의 인스턴스를 생성합니다. 제공된 HttpClient 는 이 인스턴스에 의해 해제되지 않으며 호출자에게 소유가 남아 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 언어 모델. 가능한 값: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 키 |
| organizationId | java.lang.String | 조직 ID (옵션) |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpClient 인스턴스 |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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
[IAIConversation](../../com.aspose.slides/iaiconversation) - 하나의 [IAIConversation](../../com.aspose.slides/iaiconversation) 인스턴스.

### close() {#close--}
```
public final void close()
```

이 인스턴스에서 사용된 리소스를 해제합니다.