---
title: SlidesAIAgent
second_title: Referencia de API de Aspose.Slides para Java
description: Proporciona funciones impulsadas por IA para procesar presentaciones.
type: docs
url: /es/com.aspose.slides/slidesaiagent/
---
**Inheritance:**
java.lang.Object
```
public class SlidesAIAgent
```

Proporciona funciones impulsadas por IA para procesar presentaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Inicializa una nueva instancia de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) con un cliente de IA personalizado. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Inicializa una nueva instancia de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando el [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) incorporado con su configuración predeterminada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduce una presentación al idioma especificado usando IA (versión sincrónica). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Genera una instancia de presentación a partir de una descripción de texto. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Genera una instancia de presentación a partir de una descripción de texto. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Inicializa una nueva instancia de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) con un cliente de IA personalizado. Use esta sobrecarga para especificar el proveedor de IA, suministrar su propio LLM o personalizar la conexión (por ejemplo, proporcionando su propio java.net.HttpURLConnection). Cualquier implementación de [IAIWebClient](../../com.aspose.slides/iaiwebclient) puede utilizarse. Para usar el [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) incorporado con su configuración predeterminada, use la sobrecarga SlidesAIAgent() en su lugar.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instancia del cliente de IA. Cualquier implementación de [IAIWebClient](../../com.aspose.slides/iaiwebclient) puede utilizarse. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Inicializa una nueva instancia de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) usando el [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) incorporado con su configuración predeterminada. El cliente se conecta al LLM propio de Aspose y no requiere configuración adicional. Para usar un cliente de IA diferente, use la sobrecarga SlidesAIAgent(IAIWebClient) en su lugar.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Traduce una presentación al idioma especificado usando IA (versión sincrónica).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación de destino |
| language | java.lang.String | Idioma de destino |

--------------------

El ejemplo a continuación usa el [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) predeterminado, que se crea mediante el constructor sin parámetros SlidesAIAgent() y se conecta al LLM propio de Aspose. Para usar un proveedor de IA diferente, suministrar su propio LLM o personalizar la conexión (por ejemplo, proporcionando su propio java.net.HttpURLConnection), pase una implementación [IAIWebClient](../../com.aspose.slides/iaiwebclient) al constructor SlidesAIAgent(IAIWebClient).

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
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Una presentación que se usará como plantilla para el diseño y la disposición, reemplazando la plantilla predeterminada.

--------------------

El ejemplo a continuación usa el [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) predeterminado, que se crea mediante el constructor sin parámetros SlidesAIAgent() y se conecta al LLM propio de Aspose. Para usar un proveedor de IA diferente, suministrar su propio LLM o personalizar la conexión (por ejemplo, proporcionando su propio java.net.HttpURLConnection), pase una implementación [IAIWebClient](../../com.aspose.slides/iaiwebclient) al constructor SlidesAIAgent(IAIWebClient).

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

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)