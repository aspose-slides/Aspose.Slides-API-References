---
title: SlidesAIAgent
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: قابلیت‌های مجهز به هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/slidesaiagent/
---
**ارث‌بری:**
java.lang.Object
```
public class SlidesAIAgent
```

قابلیت‌های مجهز به هوش مصنوعی برای پردازش ارائه‌ها را فراهم می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | سازنده SlidesAIAgent |
## متدها

| متد | توضیح |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | یک ارائه را به زبان مشخص شده با استفاده از هوش مصنوعی ترجمه می‌کند (نسخه هماهنگ). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | یک نمونه ارائه را از توصیف متنی تولید می‌کند. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | یک نمونه ارائه را از توصیف متنی تولید می‌کند. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


سازنده SlidesAIAgent

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | نمونهٔ کلاینت AI |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


یک ارائه را به زبان مشخص شده با استفاده از هوش مصنوعی ترجمه می‌کند (نسخه هماهنگ).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه هدف |
| language | java.lang.String | زبان هدف

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


یک نمونه ارائه را از توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متن را در زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متن. |
| presentationContentAmount | int | مقدار محتوا در ارائهٔ خروجی.

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

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


یک نمونه ارائه را از توصیف متنی تولید می‌کند. یک موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متن را در زبان مورد نیاز فراهم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| description | java.lang.String | موضوع، ایده‌ها، نقل‌قول‌ها یا قطعات متن. |
| presentationContentAmount | int | مقدار محتوی در ارائهٔ خروجی. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | یک ارائه برای استفاده به عنوان قالب برای چینش و طراحی، که قالب پیش‌فرض را جایگزین می‌کند.

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

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)