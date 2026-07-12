---
title: SlidesAIAgent
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Proporciona funciones impulsadas por IA para procesar presentaciones.
type: docs
url: /es/com.aspose.slides/slidesaiagent/
---
**Herencia:**
java.lang.Object
```
public class SlidesAIAgent
```

Proporciona funciones impulsadas por IA para procesar presentaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | SlidesAIAgent constructor |
## Métodos

| Método | Descripción |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduce una presentación al idioma especificado usando IA (versión síncrona). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genera una instancia de presentación a partir de una descripción de texto. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genera una instancia de presentación a partir de una descripción de texto. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


SlidesAIAgent constructor

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | instancia del cliente IA |

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Traduce una presentación al idioma especificado usando IA (versión síncrona).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | presentación de destino |
| language | java.lang.String | idioma de destino

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


Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| description | java.lang.String | El tema, ideas, citas o fragmentos de texto. |
| presentationContentAmount | int | La cantidad de contenido en la presentación resultante.

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

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| description | java.lang.String | El tema, ideas, citas o fragmentos de texto. |
| presentationContentAmount | int | La cantidad de contenido en la presentación resultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Una presentación para usar como plantilla de diseño y distribución, reemplazando la plantilla predeterminada.

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

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)