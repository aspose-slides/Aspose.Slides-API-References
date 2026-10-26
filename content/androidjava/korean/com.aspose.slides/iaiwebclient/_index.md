---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /ko/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI 웹 클라이언트 인터페이스. 이 인터페이스는 다양한 AI 언어 모델을 교체할 수 있게 합니다. 이 인터페이스를 구현하는 클래스는 SlidesAIAgent와 함께 사용하도록 설계되었습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

AI 모델에 제공된 HttpConnection 인스턴스를 사용하여 채팅 명령을 전송하고 해당 명령에 대한 응답 메시지를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String | AI 모델이 처리할 명령 또는 메시지입니다. |

**반환값:**
java.lang.String - 주어진 명령에 대한 응답으로 AI 모델이 생성한 메시지.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

대화 인스턴스를 생성합니다. 일반 AI 호출과 달리 대화는 전체 컨텍스트를 유지합니다.

**반환값:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - [IAIConversation](../../com.aspose.slides/iaiconversation) 인스턴스.