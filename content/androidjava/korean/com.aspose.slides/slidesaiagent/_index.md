---
title: SlidesAIAgent
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션 처리를 위한 AI 기반 기능을 제공합니다.
type: docs
url: /ko/com.aspose.slides/slidesaiagent/
---
**상속:**
java.lang.Object
```
public class SlidesAIAgent
```

프레젠테이션 처리를 위한 AI 기반 기능을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | AI를 사용하여 프레젠테이션을 지정된 언어로 변환합니다 (동기 버전). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | 텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

SlidesAIAgent 생성자

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | AI 클라이언트 인스턴스 |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```

AI를 사용하여 프레젠테이션을 지정된 언어로 변환합니다 (동기 버전).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 대상 프레젠테이션 |
| language | java.lang.String | 대상 언어

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

텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요 언어로 주제, 아이디어, 인용문 또는 텍스트 스니펫을 제공하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| description | java.lang.String | 주제, 아이디어, 인용문 또는 텍스트 스니펫. |
| presentationContentAmount | int | 결과 프레젠테이션의 콘텐츠 양.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
 OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient);
     IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief);
     pres.save("result.pptx", SaveFormat.Pptx);
 } finally {
     if (aiWebClient != null) aiWebClient.close();
 }
``` |

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

텍스트 설명으로부터 프레젠테이션 인스턴스를 생성합니다. 필요 언어로 주제, 아이디어, 인용문 또는 텍스트 스니펫을 제공하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| description | java.lang.String | 주제, 아이디어, 인용문 또는 텍스트 스니펫. |
| presentationContentAmount | int | 결과 프레젠테이션의 콘텐츠 양. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | 레이아웃 및 디자인을 위한 템플릿으로 사용할 프레젠테이션으로, 기본 템플릿을 대체합니다.

```
String prompt = "Generate a presentation about Aspose.Slides for Android via Java. Highlight its key features, use cases, and explain why it is better than its competitors.";
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

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)