---
title: SlidesAIAgent
second_title: Référence API Aspose.Slides pour Java
description: Fournit des fonctionnalités alimentées par l'IA pour le traitement des présentations.
type: docs
url: /fr/com.aspose.slides/slidesaiagent/
---
**Héritage :**
java.lang.Object
```
public class SlidesAIAgent
```

Fournit des fonctionnalités alimentées par l'IA pour le traitement des présentations.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Initialise une nouvelle instance de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) avec un client IA personnalisé. |
| [SlidesAIAgent()](#SlidesAIAgent--) | Initialise une nouvelle instance de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) en utilisant le [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) intégré avec sa configuration par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduit une présentation dans la langue spécifiée en utilisant l'IA (version synchrone). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Génère une instance de présentation à partir d’une description textuelle. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Génère une instance de présentation à partir d’une description textuelle. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```

Initialise une nouvelle instance de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) avec un client IA personnalisé. Utilisez cette surcharge pour spécifier le fournisseur d'IA, fournir votre propre LLM, ou personnaliser la connexion (par exemple, en fournissant votre propre java.net.HttpURLConnection). Toute implémentation de [IAIWebClient](../../com.aspose.slides/iaiwebclient) peut être utilisée. Pour utiliser le [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) intégré avec sa configuration par défaut, utilisez la surcharge SlidesAIAgent() à la place.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instance du client IA. Toute implémentation de [IAIWebClient](../../com.aspose.slides/iaiwebclient) peut être utilisée. |

### SlidesAIAgent() {#SlidesAIAgent--}
```
public SlidesAIAgent()
```

Initialise une nouvelle instance de [SlidesAIAgent](../../com.aspose.slides/slidesaiagent) en utilisant le [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) intégré avec sa configuration par défaut. Le client se connecte au LLM propre à Aspose et ne nécessite aucune configuration supplémentaire. Pour utiliser un client IA différent, utilisez la surcharge SlidesAIAgent(IAIWebClient) à la place.

### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public final void translate(IPresentation presentation, String language)
```

Traduit une présentation dans la langue spécifiée en utilisant l'IA (version synchrone).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation cible |
| language | java.lang.String | Langue cible

--------------------

L’exemple ci-dessous utilise le [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) par défaut, qui est créé par le constructeur SlidesAIAgent() sans paramètres et se connecte au LLM propre à Aspose. Pour utiliser un fournisseur d'IA différent, fournir votre propre LLM, ou personnaliser la connexion (par exemple, en fournissant votre propre java.net.HttpURLConnection), passez une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) au constructeur SlidesAIAgent(IAIWebClient).

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

Génère une instance de présentation à partir d’une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation résultante.

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

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```

Génère une instance de présentation à partir d’une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation résultante. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Une présentation à utiliser comme modèle pour la mise en page et le design, remplaçant le modèle par défaut.

--------------------

L’exemple ci-dessous utilise le [AsposeAIWebClient](../../com.aspose.slides/asposeaiwebclient) par défaut, qui est créé par le constructeur SlidesAIAgent() sans paramètres et se connecte au LLM propre à Aspose. Pour utiliser un fournisseur d'IA différent, fournir votre propre LLM, ou personnaliser la connexion (par exemple, en fournissant votre propre java.net.HttpURLConnection), passez une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) au constructeur SlidesAIAgent(IAIWebClient).

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

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)