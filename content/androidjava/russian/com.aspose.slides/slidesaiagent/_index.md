---
title: SlidesAIAgent
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет функции, основанные на ИИ, для обработки презентаций.
type: docs
url: /ru/com.aspose.slides/slidesaiagent/
---
**Наследование:**
java.lang.Object
```
public class SlidesAIAgent
```

Предоставляет функции, основанные на AI, для обработки презентаций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с пользовательским AI client. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с использованием встроенного [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с его конфигурацией по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Переводит презентацию на указанный язык, используя AI (синхронная версия). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Создаёт экземпляр презентации из текстового описания. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Создаёт экземпляр презентации из текстового описания. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с пользовательским AI client. Используйте эту перегрузку, чтобы указать поставщика AI, предоставить свою собственную LLM или настроить соединение (например, предоставив свой java.net.HttpURLConnection). Можно использовать любую реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient). Чтобы использовать встроенный [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с конфигурацией по умолчанию, используйте перегрузку SlidesAIAgent() вместо этого.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Экземпляр AI client. Можно использовать любую реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с использованием встроенного [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с его конфигурацией по умолчанию. Клиент подключается к собственному LLM Aspose и не требует дополнительной настройки. Чтобы использовать другой AI client, используйте перегрузку SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Переводит презентацию на указанный язык, используя AI (синхронная версия).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Целевая презентация |
| language | java.lang.String | Целевой язык

--------------------

Пример ниже использует [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) по умолчанию, который создаётся конструктором SlidesAIAgent() без параметров и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика AI, предоставить свою LLM или настроить соединение (например, предоставив свой java.net.HttpURLConnection), передайте реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient) в конструктор SlidesAIAgent(IAIWebClient).

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

Создаёт экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| description | java.lang.String | Тема, идеи, цитаты или фрагменты текста. |
| presentationContentAmount | int | Количество содержимого в полученной презентации. |

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
**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Создаёт экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| description | java.lang.String | Тема, идеи, цитаты или фрагменты текста. |
| presentationContentAmount | int | Количество содержимого в полученной презентации. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, используемая в качестве шаблона для макета и дизайна, заменяющая шаблон по умолчанию. |
--------------------

Пример ниже использует [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) по умолчанию, который создаётся конструктором SlidesAIAgent() без параметров и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика AI, предоставить свою LLM или настроить соединение (например, предоставив свой java.net.HttpURLConnection), передайте реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient) в конструктор SlidesAIAgent(IAIWebClient).

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
**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)