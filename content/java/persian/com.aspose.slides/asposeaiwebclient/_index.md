---
title: AsposeAIWebClient
second_title: مرجع API Aspose.Slides برای Java
description: یک پیاده‌سازی داخلی که به LLM خود Aspose متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/asposeaiwebclient/
---
**ارث‌بری:**  
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به LLM خود Aspose متصل می‌شود. این مشتری پیش‌فرض است که توسط سازنده بدون پارامتر  SlidesAIAgent()  استفاده می‌شود.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از HttpClient مدیریت‌شده خارجی به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به URL نقطه انتهای سفارشی متصل می‌شود. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از HttpClient مدیریت‌شده خارجی به URL نقطه انتهای سفارشی متصل می‌شود. |

## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | یک نمونه از گفتگو ایجاد می‌کند. |
| [dispose()](#dispose--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. این مشتری توسط سازنده بدون پارامتر  SlidesAIAgent()  استفاده می‌شود، بنابراین ساخت صریح آن فقط زمانی لازم است که مشتری را مستقیماً به سازنده  SlidesAIAgent(IAIWebClient)  پاس بدهید.

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

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از HttpClient مدیریت‌شده خارجی به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. HttpClient ارائه‌شده توسط این نمونه از بین نمی‌رود و مالکیت آن برای فراخواننده باقی می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpClient مدیریت‌شده خارجی. |
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

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به URL نقطه انتهای سفارشی متصل می‌شود. از این overload زمانی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد؛ در غیر این صورت، از overload  AsposeAIWebClient()  با URL پیش‌فرض استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطه انتهای Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |
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

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از HttpClient مدیریت‌شده خارجی به URL نقطه انتهای سفارشی متصل می‌شود. HttpClient ارائه‌شده توسط این نمونه از بین نمی‌رود و مالکیت آن برای فراخواننده باقی می‌ماند. از این overload زمانی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد و می‌خواهید HttpClient خود را فراهم کنید؛ اگر فقط به HttpClient خود با URL پیش‌فرض نیاز دارید، به جای آن از overload  AsposeAIWebClient(HttpClient)  استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطه انتهای Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |
| httpClient | java.net.HttpURLConnection | یک نمونه HttpClient مدیریت‌شده خارجی. |
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

دستور چت را با استفاده از یک نمونه HttpConnection به مدل AI ارسال می‌کند و پیام پاسخ را به دستور داده شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String |  |
**بازگشت:**  
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونه از گفتگو ایجاد می‌کند. بر خلاف فراخوانی‌های معمولی AI، گفتگوها تمام زمینه را نگه می‌دارند.

**بازگشت:**  
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونه [IAIConversation](../../com.aspose.slides/iaiconversation)

### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.