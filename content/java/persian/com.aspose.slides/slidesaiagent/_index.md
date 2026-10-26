---
title: SlidesAIAgent
second_title: مرجع API Aspose.Slides برای Java
description: قابلیت‌های مبتنی بر هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/slidesaiagent/
---
**ارث بری:**
java.lang.Object
```
public class SlidesAIAgent
```

قابلیت‌های مبتنی بر هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با یک مشتری AI سفارشی مقداردهی اولیه می‌کند. |
| [SlidesAIAgent()](#SlidesAIAgent--) | یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) داخلی با پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | یک ارائه را به زبان مشخص شده با استفاده از AI ترجمه می‌کند (نسخهٔ همزمان). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | یک نمونهٔ ارائه را بر اساس توضیح متنی ایجاد می‌کند. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | یک نمونهٔ ارائه را بر اساس توضیح متنی ایجاد می‌کند. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با یک مشتری AI سفارشی مقداردهی اولیه می‌کند. از این بارگذاری‌مجدد برای مشخص کردن ارائه‌دهندهٔ AI، تامین LLM خودتان، یا سفارشی‌سازی اتصال (به عنوان مثال، با ارائهٔ java.net.HttpURLConnection خود) استفاده کنید. می‌توان از هر پیاده‌سازی از [IAIWebClient](../../com.aspose.slides/iaiwebclient) استفاده کرد. برای استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) داخلی با پیکربندی پیش‌فرض آن، به جای آن از بارگذاری‌مجدد SlidesAIAgent() استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | نمونهٔ مشتری AI. می‌توان از هر پیاده‌سازی از [IAIWebClient](../../com.aspose.slides/iaiwebclient) استفاده کرد. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) داخلی با پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. این مشتری به LLM خود Aspose متصل می‌شود و نیازی به پیکربندی اضافی ندارد. برای استفاده از مشتری AI دیگر، به جای آن از بارگذاری‌مجدد SlidesAIAgent(IAIWebClient) استفاده کنید.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

یک ارائه را به زبان مشخص شده با استفاده از AI ترجمه می‌کند (نسخهٔ همزمان).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه هدف |
| language | java.lang.String | زبان هدف

--------------------

مثال زیر از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) پیش‌فرض استفاده می‌کند که توسط سازندهٔ بدون پارامتر SlidesAIAgent() ایجاد شده و به LLM خود Aspose متصل می‌شود. برای استفاده از ارائه‌دهندهٔ AI متفاوت، LLM خود را فراهم کنید، یا اتصال را سفارشی کنید (به عنوان مثال، با ارائهٔ java.net.HttpURLConnection خود)، یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) را به سازندهٔ SlidesAIAgent(IAIWebClient) پاس بدهید.

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

یک نمونهٔ ارائه را بر اساس توضیح متنی ایجاد می‌کند. یک موضوع، ایده، نقل قول یا قطعه‌های متن را به زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل قول‌ها یا قطعه‌های متن. |
| presentationContentAmount | int | مقدار محتوای موجود در ارائهٔ حاصل. |

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

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)

### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

یک نمونهٔ ارائه را بر اساس توضیح متنی ایجاد می‌کند. یک موضوع، ایده، نقل قول یا قطعه‌های متن را به زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل قول‌ها یا قطعه‌های متن. |
| presentationContentAmount | int | مقدار محتوای موجود در ارائهٔ حاصل. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | یک ارائه برای استفاده به عنوان قالب برای چیدمان و طراحی، جایگزین قالب پیش‌فرض. |

--------------------

مثال زیر از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) پیش‌فرض استفاده می‌کند که توسط سازندهٔ بدون پارامتر SlidesAIAgent() ایجاد شده و به LLM خود Aspose متصل می‌شود. برای استفاده از ارائه‌دهندهٔ AI متفاوت، LLM خود را فراهم کنید، یا اتصال را سفارشی کنید (به عنوان مثال، با ارائهٔ java.net.HttpURLConnection خود)، یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) را به سازندهٔ SlidesAIAgent(IAIWebClient) پاس بدهید.

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

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)