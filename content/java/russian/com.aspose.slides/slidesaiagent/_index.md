---
title: SlidesAIAgent
second_title: Справка API Aspose.Slides для Java
description: Обеспечивает функции ИИ для обработки презентаций.
type: docs
url: /ru/com.aspose.slides/slidesaiagent/
---
**Наследование:**
java.lang.Object
```
public class SlidesAIAgent
```

Обеспечивает функции ИИ для обработки презентаций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с пользовательским клиентом ИИ. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с использованием встроенного [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с его конфигурацией по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Переводит презентацию на указанный язык с помощью ИИ (синхронная версия). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Генерирует экземпляр презентации из текстового описания. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Генерирует экземпляр презентации из текстового описания. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с пользовательским клиентом ИИ. Используйте эту перегрузку, чтобы указать поставщика ИИ, предоставить собственную LLM или настроить соединение (например, предоставив собственный java.net.HttpURLConnection). Может быть использована любая реализация [IAIWebClient](../../com.aspose.slides/iaiwebclient). Чтобы использовать встроенный [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с его конфигурацией по умолчанию, используйте перегрузку SlidesAIAgent().

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Экземпляр клиента ИИ. Может быть использована любая реализация [IAIWebClient](../../com.aspose.slides/iaiwebclient). |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Инициализирует новый экземпляр [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) с использованием встроенного [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) с его конфигурацией по умолчанию. Клиент подключается к собственному LLM Aspose и не требует дополнительной настройки. Чтобы использовать другой клиент ИИ, используйте перегрузку SlidesAIAgent(IAIWebClient).

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Переводит презентацию на указанный язык с помощью ИИ (синхронная версия).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Целевая презентация |
| language | java.lang.String | Целевой язык

--------------------

Пример ниже использует стандартный [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), который создаётся параметр-less конструктором SlidesAIAgent() и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика ИИ, предоставить свою LLM или настроить соединение (например, предоставив собственный java.net.HttpURLConnection), передайте реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient) в конструктор SlidesAIAgent(IAIWebClient).

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

Генерирует экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| description | java.lang.String | Тема, идеи, цитаты или фрагменты текста. |
| presentationContentAmount | int | Объём содержимого в результирующей презентации.

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

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Генерирует экземпляр презентации из текстового описания. Укажите тему, идеи, цитаты или фрагменты текста на требуемом языке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| description | java.lang.String | Тема, идеи, цитаты или фрагменты текста. |
| presentationContentAmount | int | Объём содержимого в результирующей презентации. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, используемая в качестве шаблона для макета и дизайна, заменяющая шаблон по умолчанию.

--------------------

Пример ниже использует стандартный [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient), который создаётся параметр-less конструктором SlidesAIAgent() и подключается к собственному LLM Aspose. Чтобы использовать другого поставщика ИИ, предоставить свою LLM или настроить соединение (например, предоставив собственный java.net.HttpURLConnection), передайте реализацию [IAIWebClient](../../com.aspose.slides/iaiwebclient) в конструктор SlidesAIAgent(IAIWebClient).

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

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)