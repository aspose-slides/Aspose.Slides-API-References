---
title: SlidesAIAgent
second_title: مرجع API Aspose.Slides برای Java
description: قابلیت‌های مبتنی بر هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/slidesaiagent/
---
**ارث‌بری:**  
java.lang.Object
```
public class SlidesAIAgent
```

امکانات مبتنی بر هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با یک مشتری سفارشی هوش مصنوعی مقداردهی اولیه می‌کند. |
| [SlidesAIAgent()](#SlidesAIAgent--) | یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) پیش‌فرض و پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | یک ارائه را به زبان مشخص شده با استفاده از هوش مصنوعی ترجمه می‌کند (نسخه همزمان). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. |

### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با یک مشتری سفارشی هوش مصنوعی مقداردهی اولیه می‌کند. از این overload برای مشخص کردن فراهم‌کننده هوش مصنوعی، فراهم کردن LLM خودتان، یا سفارشی‌کردن اتصال (مثلاً با فراهم کردن java.net.HttpURLConnection خود) استفاده کنید. هر پیاده‌سازی از [IAIWebClient](../../com.aspose.slides/iaiwebclient) می‌تواند استفاده شود. برای استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) پیش‌فرض با پیکربندی پیش‌فرض، به جای آن overload SlidesAIAgent() را استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | نمونه مشتری هوش مصنوعی. هر پیاده‌سازی از [IAIWebClient](../../com.aspose.slides/iaiwebclient) می‌تواند استفاده شود. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

یک نمونه جدید از [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) را با استفاده از [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) پیش‌فرض و پیکربندی پیش‌فرض آن مقداردهی اولیه می‌کند. این مشتری به LLM اختصاصی Aspose متصل می‌شود و نیازی به پیکربندی اضافی ندارد. برای استفاده از مشتری هوش مصنوعی متفاوت، به جای آن overload SlidesAIAgent(IAIWebClient) را استفاده کنید.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

یک ارائه را به زبان مشخص شده با استفاده از هوش مصنوعی ترجمه می‌کند (نسخه همزمان).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه هدف |
| language | java.lang.String | زبان هدف |

--------------------

مثال زیر از پیش‌فرض [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) استفاده می‌کند که توسط سازنده بدون پارامتر SlidesAIAgent() ایجاد شده و به LLM اختصاصی Aspose متصل می‌شود. برای استفاده از فراهم‌کننده هوش مصنوعی متفاوت، LLM خودتان را فراهم کنید یا اتصال را سفارشی کنید (مثلاً با فراهم کردن java.net.HttpURLConnection خود)، یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) را به سازنده SlidesAIAgent(IAIWebClient) پاس دهید.

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

یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل قول‌ها یا قطعات متن را به زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل قول‌ها یا قطعات متن. |
| presentationContentAmount | int | مقدار محتوا در ارائهٔ خروجی. |

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

یک نمونه ارائه را از یک توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل قول‌ها یا قطعات متن را به زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل قول‌ها یا قطعات متن. |
| presentationContentAmount | int | مقدار محتوا در ارائهٔ خروجی. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که به عنوان قالب برای چیدمان و طراحی استفاده می‌شود و قالب پیش‌فرض را جایگزین می‌کند. |

--------------------

مثال زیر از پیش‌فرض [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) استفاده می‌کند که توسط سازنده بدون پارامتر SlidesAIAgent() ایجاد شده و به LLM اختصاصی Aspose متصل می‌شود. برای استفاده از فراهم‌کننده هوش مصنوعی متفاوت، LLM خودتان را فراهم کنید یا اتصال را سفارشی کنید (مثلاً با فراهم کردن java.net.HttpURLConnection خود)، یک پیاده‌سازی [IAIWebClient](../../com.aspose.slides/iaiwebclient) را به سازنده SlidesAIAgent(IAIWebClient) پاس دهید.

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