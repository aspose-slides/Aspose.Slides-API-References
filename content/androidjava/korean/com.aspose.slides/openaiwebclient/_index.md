---
title: OpenAIWebClient
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 내장형 경량 OpenAI 웹 클라이언트
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

내장형 경량 OpenAI 웹 클라이언트
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | OpenAI Web 클라이언트의 인스턴스를 생성합니다. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | OpenAI Web 클라이언트의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | 외부에서 관리되는 인스턴스를 사용하여 AI 모델에 채팅 지시를 보내고 해당 지시의 응답 메시지를 반환합니다. |
| [createConversation()](#createConversation--) | 대화 인스턴스를 생성합니다. |
| [close()](#close--) | 이 인스턴스가 사용한 리소스를 해제합니다. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```


OpenAI Web 클라이언트의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 언어 모델. 가능한 값: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 키 |
| organizationId | java.lang.String | 조직 ID(선택 사항) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


OpenAI Web 클라이언트의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| model | java.lang.String | OpenAI 언어 모델. 가능한 값: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | OpenAI API 키 |
| organizationId | java.lang.String | 조직 ID(선택 사항) |
| httpClient | java.net.HttpURLConnection | 외부에서 관리되는 HttpURLConnection 인스턴스입니다. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


외부에서 관리되는 인스턴스를 사용하여 AI 모델에 채팅 지시를 보내고 해당 지시의 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String | AI 모델이 처리할 지시 또는 메시지 |

**반환값:**  
java.lang.String - 주어진 지시에 대한 응답으로 AI 모델이 생성한 메시지.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


대화 인스턴스를 생성합니다. 일반 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다.

**반환값:**  
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) 인스턴스.

### close() {#close--}
```
public final void close()
```


이 인스턴스가 사용한 리소스를 해제합니다.