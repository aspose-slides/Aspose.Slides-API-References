---
title: AsposeAIWebClient
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک پیاده‌سازی داخلی که به LLM خود Aspose متصل می‌شود.
type: docs
url: /fa/com.aspose.slides/asposeaiwebclient/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) داخلی که به LLM خود Aspose متصل می‌شود. این یک مشتری پیش‌فرض است که توسط سازنده بدون پارامتر  SlidesAIAgent()  استفاده می‌شود.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به یک URL نقطه انتهای سفارشی متصل می‌شود. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به یک URL نقطه انتهای سفارشی متصل می‌شود. |

## متدها

| متد | توضیح |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | یک دستور چت را به مدل AI ارسال می‌کند و پیام پاسخ را به دستور داده شده برمی‌گرداند. |
| [createConversation()](#createConversation--) | یک نمونهٔ گفتگو ایجاد می‌کند. |
| [dispose()](#dispose--) | منابع استفاده‌شده توسط این نمونه را آزاد می‌کند. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. این مشتری توسط سازنده بدون پارامتر  SlidesAIAgent()  استفاده می‌شود، بنابراین ایجاد صریح آن فقط در زمانی لازم است که مشتری را مستقیماً به سازنده  SlidesAIAgent(IAIWebClient)  پاس دهید.

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

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به نقطه انتهای پیش‌فرض Aspose LLM متصل می‌شود. HttpURLConnection ارائه‌شده توسط این نمونه حذف نمی‌شود و متعلق به فراخواننده می‌ماند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | یک نمونه  HttpURLConnection  مدیریت‌شده خارجی. |
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
``` |

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که به یک URL نقطه انتهای سفارشی متصل می‌شود. از این بارگذاری زمانی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد؛ در غیر این صورت، از بارگذاری  AsposeAIWebClient()  با URL پیش‌فرض استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطه انتهای Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |
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
``` |

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

یک نمونه از مشتری وب Aspose AI ایجاد می‌کند که با استفاده از یک  HttpURLConnection  مدیریت‌شده خارجی به یک URL نقطه انتهای سفارشی متصل می‌شود. HttpURLConnection ارائه‌شده توسط این نمونه حذف نمی‌شود و متعلق به فراخواننده می‌ماند. از این بارگذاری زمانی استفاده کنید که URL توسط تیم Aspose.Slides ارائه شده باشد و بخواهید HttpURLConnection خود را فراهم کنید؛ اگر فقط به HttpURLConnection خود با URL پیش‌فرض نیاز دارید، به جای آن از بارگذاری  AsposeAIWebClient(HttpURLConnection)  استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | java.lang.String | URL نقطه انتهای Aspose LLM که توسط تیم Aspose.Slides ارائه شده است. |
| httpClient | java.net.HttpURLConnection | یک نمونه  HttpURLConnection  مدیریت‌شده خارجی. |
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
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

یک دستور چت را به مدل AI ارسال می‌کند و پیام پاسخ را به دستور داده شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| instruction | java.lang.String | دستور یا پیام برای پردازش توسط مدل AI. |

**بازگشت:**
java.lang.String - پیام تولید شده توسط مدل AI در پاسخ به دستور داده شده.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

یک نمونهٔ گفتگو ایجاد می‌کند. بر خلاف تماس‌های معمولی AI، گفتگوها کل زمینه را حفظ می‌کنند.

**بازگشت:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - یک نمونهٔ [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

منابع استفاده‌شده توسط این نمونه را آزاد می‌کند.