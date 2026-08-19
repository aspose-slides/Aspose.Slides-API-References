---
title: AsposeAIWebClient
second_title: Aspose.Slides برای Java مرجع API
description: یک پیاده‌سازی داخلی که به LLM اختصاصی Aspose متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/asposeaiwebclient/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به LLM اختصاصی Aspose متصل می‌شود. این مشتری پیش‌فرضی است که توسط سازندهٔ بدون پارامتر  SlidesAIAgent()  استفاده می‌شود.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | یک نمونه از Aspose AI web client که به نقطهٔ پایان پیش‌فرض Aspose LLM متصل می‌شود را ایجاد می‌کند. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | یک نمونه از Aspose AI web client که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به نقطهٔ پایان پیش‌فرض Aspose LLM متصل می‌شود را ایجاد می‌کند. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | یک نمونه از Aspose AI web client که به URL نقطهٔ پایان سفارشی متصل می‌شود را ایجاد می‌کند. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از Aspose AI web client که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به URL نقطهٔ پایان سفارشی متصل می‌شود را ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | یک دستور چت را به مدل AI می‌فرستد و پیام پاسخ را برای دستور داده‌شده برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونهٔ گفت‌وگو ایجاد می‌کند. |
| [dispose()](#dispose--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

یک نمونه از Aspose AI web client که به نقطهٔ پایان پیش‌فرض Aspose LLM متصل می‌شود را ایجاد می‌کند. این مشتری توسط سازندهٔ بدون پارامتر  SlidesAIAgent()  استفاده می‌شود، بنابراین ایجاد صریح آن تنها زمانی لازم است که مشتری را مستقیماً به سازندهٔ  SlidesAIAgent(IAIWebClient)  پاس بدهید.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

یک نمونه از Aspose AI web client که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به نقطهٔ پایان پیش‌فرض Aspose LLM متصل می‌شود را ایجاد می‌کند.  HttpURLConnection  ارائه‌شده توسط این نمونه حذف نمی‌شود و متعلق به فراخواننده می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | یک نمونهٔ  HttpURLConnection  مدیریت‌شده خارجی. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
```

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

یک نمونه از Aspose AI web client که به URL نقطهٔ پایان سفارشی متصل می‌شود را ایجاد می‌کند. از این overload وقتی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد؛ در غیر این صورت، از overload  AsposeAIWebClient()  با URL پیش‌فرض استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطهٔ پایان Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
```

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

یک نمونه از Aspose AI web client که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به URL نقطهٔ پایان سفارشی متصل می‌شود را ایجاد می‌کند.  HttpURLConnection  ارائه‌شده توسط این نمونه حذف نمی‌شود و متعلق به فراخواننده می‌ماند. از این overload وقتی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد و بخواهید  HttpURLConnection  خودتان را فراهم کنید؛ اگر فقط به  HttpURLConnection  خودتان با URL پیش‌فرض نیاز دارید، به جای آن از overload  AsposeAIWebClient(HttpURLConnection)  استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطهٔ پایان Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |
| httpClient | java.net.HttpURLConnection | یک نمونهٔ  HttpURLConnection  مدیریت‌شده خارجی. |

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
```

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

یک دستور چت را به مدل AI می‌فرستد و پیام پاسخ را برای دستور داده‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام مورد پردازش توسط مدل AI. |

**بازگشت:**
java.lang.String - پیامی که توسط مدل AI در پاسخ به دستور داده‌شده تولید می‌شود.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونهٔ گفت‌وگو ایجاد می‌کند. برخلاف تماس‌های معمولی AI، گفت‌وگوها تمام زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونهٔ [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.