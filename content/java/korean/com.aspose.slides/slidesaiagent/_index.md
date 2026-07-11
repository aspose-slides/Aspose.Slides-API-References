---
title: SlidesAIAgent
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션을 처리하기 위한 AI 기반 기능을 제공합니다.
type: docs
url: /ko/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

프레젠테이션을 처리하기 위한 AI 기반 기능을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | 사용자 정의 AI 클라이언트를 사용하여 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent)의 새 인스턴스를 초기화합니다. |
| [SlidesAIAgent()](#SlidesAIAgent--) | 기본 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)를 사용하고 기본 구성으로 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent)의 새 인스턴스를 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI를 사용하여 지정된 언어로 프레젠테이션을 번역합니다(동기 버전). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

사용자 정의 AI 클라이언트를 사용하여 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent)의 새 인스턴스를 초기화합니다. 이 오버로드를 사용하여 AI 제공자를 지정하거나 자체 LLM을 제공하거나 연결을 사용자 지정할 수 있습니다(예: 자체 java.net.HttpURLConnection을 제공). [IAIWebClient](../../com.aspose.slides/iaiwebclient)의 모든 구현을 사용할 수 있습니다. 기본 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)를 기본 구성으로 사용하려면 SlidesAIAgent() 오버로드를 대신 사용하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 클라이언트 인스턴스. [IAIWebClient](../../com.aspose.slides/iaiwebclient)의 모든 구현을 사용할 수 있습니다. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

기본 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)를 사용하고 기본 구성으로 [SlidesAIAgent](../../com.aspose.slides/slidesaiagent)의 새 인스턴스를 초기화합니다. 클라이언트는 Aspose 자체 LLM에 연결되며 추가 설정이 필요하지 않습니다. 다른 AI 클라이언트를 사용하려면 SlidesAIAgent(IAIWebClient) 오버로드를 사용하십시오.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

AI를 사용하여 지정된 언어로 프레젠테이션을 번역합니다(동기 버전).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 대상 프레젠테이션 |
| language | java.lang.String | 대상 언어 |

--------------------

아래 예제는 파라미터가 없는 SlidesAIAgent() 생성자로 생성된 기본 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)를 사용하며 Aspose 자체 LLM에 연결합니다. 다른 AI 제공자를 사용하거나 자체 LLM을 제공하거나 연결을 사용자 지정하려면(예: 자체 java.net.HttpURLConnection을 제공) SlidesAIAgent(IAIWebClient) 생성자에 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현을 전달하십시오.

```
Presentation presentation = new Presentation("Presentation.pptx");
 try {
     IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     aiAgent.translate(presentation, "spanish");
     presentation.save("translated.pptx", SaveFormat.Pptx);
 } finally {
     if (presentation != null) presentation.dispose();
 }
``` |

### generatePresentation(String description, int presentationContentAmount) {#generatePresentation-java.lang.String-int-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount)
```

텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 스니펫을 제공하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| description | java.lang.String | 주제, 아이디어, 인용문 또는 텍스트 스니펫 |
| presentationContentAmount | int | 결과 프레젠테이션에 포함될 콘텐츠 양 |

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요한 언어로 주제, 아이디어, 인용문 또는 텍스트 스니펫을 제공하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| description | java.lang.String | 주제, 아이디어, 인용문 또는 텍스트 스니펫 |
| presentationContentAmount | int | 결과 프레젠테이션에 포함될 콘텐츠 양 |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 레이아웃 및 디자인을 위한 템플릿으로 사용할 프레젠테이션이며, 기본 템플릿을 교체합니다. |

--------------------

아래 예제는 파라미터가 없는 SlidesAIAgent() 생성자로 생성된 기본 [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient)를 사용하며 Aspose 자체 LLM에 연결합니다. 다른 AI 제공자를 사용하거나 자체 LLM을 제공하거나 연결을 사용자 지정하려면(예: 자체 java.net.HttpURLConnection을 제공) SlidesAIAgent(IAIWebClient) 생성자에 [IAIWebClient](../../com.aspose.slides/iaiwebclient) 구현을 전달하십시오.

```
String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 IPresentation template = new Presentation("masterPresentation.pptx");
 try {
     OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
     try {
         SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
         IPresentation pres =
             aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template);
         pres.save("result.pptx", SaveFormat.Pptx);
     } finally {
         if (aiWebClient != null) aiWebClient.close();
     }
 } finally {
     if (template != null) template.dispose();
 }
``` |

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)