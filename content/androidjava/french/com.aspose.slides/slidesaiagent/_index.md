---
title: SlidesAIAgent
second_title: Aspose.Slides pour Android via la référence API Java
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
| [SlidesAIAgent(IAIWebClient aiClient)](#SlidesAIAgent-com.aspose.slides.IAIWebClient-) | Constructeur SlidesAIAgent |
## Méthodes

| Méthode | Description |
| --- | --- |
| [translate(IPresentation presentation, String language)](#translate-com.aspose.slides.IPresentation-java.lang.String-) | Traduit une présentation dans la langue spécifiée à l'aide de l'IA (version synchrone). |
| [generatePresentation(String description, int presentationContentAmount)](#generatePresentation-java.lang.String-int-) | Génère une instance de présentation à partir d'une description texte. |
| [generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)](#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-) | Génère une instance de présentation à partir d'une description texte. |
### SlidesAIAgent(IAIWebClient aiClient) {#SlidesAIAgent-com.aspose.slides.IAIWebClient-}
```
public SlidesAIAgent(IAIWebClient aiClient)
```


Constructeur SlidesAIAgent

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| aiClient | [IAIWebClient](../../com.aspose.slides/iaiwebclient) | Instance du client IA |
### translate(IPresentation presentation, String language) {#translate-com.aspose.slides.IPresentation-java.lang.String-}
```
public void translate(IPresentation presentation, String language)
```


Traduit une présentation dans la langue spécifiée à l'aide de l'IA (version synchrone).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation cible |
| language | java.lang.String | Langue cible

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


Génère une instance de présentation à partir d'une description texte. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation générée.

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
**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate) {#generatePresentation-java.lang.String-int-com.aspose.slides.IPresentation-}
```
public final IPresentation generatePresentation(String description, int presentationContentAmount, IPresentation presentationTemplate)
```


Génère une instance de présentation à partir d'une description texte. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| description | java.lang.String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation générée. |
| presentationTemplate | [IPresentation](../../com.aspose.slides/ipresentation) | Une présentation à utiliser comme modèle pour la mise en page et le design, remplaçant le modèle par défaut.

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
**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)