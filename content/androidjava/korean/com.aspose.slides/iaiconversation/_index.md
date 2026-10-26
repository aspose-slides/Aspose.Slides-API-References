---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /ko/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

대화 인스턴스를 나타냅니다. 일반 AI 호출과 달리, 대화는 전체 컨텍스트를 유지합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 전체 컨텍스트를 포함한 대화 요청 메시지를 보내고 응답을 반환합니다. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

전체 컨텍스트를 포함한 대화 요청 메시지를 보내고 응답을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| instruction | java.lang.String | AI 모델이 처리할 지시 또는 메시지. |

**반환값:**
java.lang.String - 주어진 지시와 대화 컨텍스트에 대한 응답으로 AI 모델이 생성한 메시지.