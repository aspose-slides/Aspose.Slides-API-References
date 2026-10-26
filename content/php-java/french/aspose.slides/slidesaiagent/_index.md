---
title: SlidesAIAgent
second_title: Aspose.Sildes pour PHP via la Référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/slidesaiagent/
---
## SlidesAIAgent classe

Fournit des fonctionnalités alimentées par l'IA pour le traitement des présentations.

### SlidesAIAgent {#SlidesAIAgent}

| Nom | Description |
| --- | --- |
| SlidesAIAgent([OpenAIWebClient](../openaiwebclient)) | fonction SlidesAIAgent |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| aiClient | [OpenAIWebClient](../openaiwebclient) | instance du client IA |

**Retour :**
SlidesAIAgent

**Erreur**

| Erreur | Condition |
| --- | --- |
| ArgumentNullException | l'instance du client IA n'est pas fournie |


---

### generatePresentation {#generatePresentation}

| Nom | Description |
| --- | --- |
| generatePresentation (String, int) | Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| description | String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation résultante. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } |

**Retour :**
[Presentation](../presentation)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | l'instruction de chat IA ne peut pas être nulle ou vide. |


---

### generatePresentation {#generatePresentation}

| Nom | Description |
| --- | --- |
| generatePresentation (String, int, [Presentation](../presentation)) | Génère une instance de présentation à partir d'une description textuelle. Fournissez un sujet, des idées, des citations ou des extraits de texte dans la langue requise. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| description | String | Le sujet, les idées, les citations ou les extraits de texte. |
| presentationContentAmount | int | La quantité de contenu dans la présentation résultante. |
| presentationTemplate | [Presentation](../presentation) | Une présentation à utiliser comme modèle pour la mise en page et le design, remplaçant le modèle par défaut. String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; IPresentation template = new Presentation("masterPresentation.pptx"); try { OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } } finally { if (template != null) template.dispose(); } |

**Retour :**
[Presentation](../presentation)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | l'instruction de chat IA ne peut pas être nulle ou vide. |


---

### translate {#translate}

| Nom | Description |
| --- | --- |
| translate ([Presentation](../presentation), String) | Traduit une présentation vers la langue spécifiée en utilisant l'IA (version synchrone). |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | Présentation cible |
| language | String | Langue cible Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |

**Retour :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | La valeur de la langue ne peut pas être nulle ou vide |