---
title: AsposeAIWebClient
second_title: Справочник API Aspose.Slides для Java
description: Встроенная реализация, которая подключается к собственному LLM Aspose.
type: docs
url: /ru/com.aspose.slides/asposeaiwebclient/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Встроенная [IAIWebClient](../../com.aspose.slides/iaiwebclient) реализация, которая подключается к собственному LLM Aspose. Это клиент по умолчанию, используемый конструктором без параметров  SlidesAIAgent() .

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке LLM Aspose по умолчанию. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке LLM Aspose по умолчанию, используя внешне управляемый  HttpClient . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки, используя внешне управляемый  HttpClient . |

## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Создает экземпляр разговора. |
| [dispose()](#dispose--) | Освобождает ресурсы, используемые этим экземпляром. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке LLM Aspose по умолчанию. Это клиент, используемый конструктором без параметров  SlidesAIAgent() , поэтому создавать его явно требуется только при передаче клиента непосредственно в конструктор  SlidesAIAgent(IAIWebClient) .

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке LLM Aspose по умолчанию, используя внешне управляемый  HttpClient . Переданный  HttpClient  не будет освобожден этим объектом и остается под контролем вызывающей стороны.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Экземпляр внешне управляемого  HttpClient . |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки. Используйте эту перегрузку, если вам предоставлен URL командой Aspose.Slides; в противном случае используйте перегрузку  AsposeAIWebClient()  с URL по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL конечной точки LLM Aspose, предоставленный командой Aspose.Slides. |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки, используя внешне управляемый  HttpClient . Переданный  HttpClient  не будет освобожден этим объектом и остается под контролем вызывающей стороны. Используйте эту перегрузку, если вам предоставлен URL командой Aspose.Slides и вы хотите задать свой  HttpClient ; если нужен только ваш  HttpClient  с URL по умолчанию, используйте перегрузку  AsposeAIWebClient(HttpClient) .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL конечной точки LLM Aspose, предоставленный командой Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Экземпляр внешне управляемого  HttpClient . |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

Отправляет инструкцию чата модели ИИ, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на заданную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Возвращает:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Создает экземпляр разговора. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.

**Возвращает:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает ресурсы, используемые этим экземпляром.