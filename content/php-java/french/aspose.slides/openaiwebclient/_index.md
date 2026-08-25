---
title: OpenAIWebClient
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/openaiwebclient/
---
## OpenAIWebClient classe

 Client Web OpenAI léger intégré

### OpenAIWebClient {#OpenAIWebClient}

| Nom | Description |
| --- | --- |
| OpenAIWebClient(String, String, String) | Crée une instance du client Web OpenAI. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| model | String | Modèle de langage OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | Clé d'API OpenAI |
| organizationId | String | ID d'organisation (facultatif) |

**Renvoie:**
OpenAIWebClient

**Erreur**

| Erreur | Condition |
| --- | --- |
| ArgumentException | La valeur du modèle texte ne peut pas être nulle ou vide |

---


### OpenAIWebClient {#OpenAIWebClient}

| Nom | Description |
| --- | --- |
| OpenAIWebClient(String, String, String, HttpURLConnection) | Crée une instance du client Web OpenAI. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| model | String | Modèle de langage OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | Clé d'API OpenAI |
| organizationId | String | ID d'organisation (facultatif) |
| httpClient | HttpURLConnection | Une instance `HttpURLConnection` gérée à l'extérieur. |

**Renvoie:**
OpenAIWebClient

**Erreur**

| Erreur | Condition |
| --- | --- |
| ArgumentException | La valeur du modèle texte ne peut pas être nulle ou vide |

---


### callChat {#callChat}

| Nom | Description |
| --- | --- |
| callChat (String) | Envoie une instruction de chat au modèle IA en utilisant une instance gérée à l'extérieur et renvoie le message de réponse à l'instruction donnée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| instruction | String | L'instruction ou le message à traiter par le modèle IA |

**Renvoie:**
String

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.OperationCanceledException | Si le thread actuel a été interrompu pendant l'attente. |

---


### close {#close}

| Nom | Description |
| --- | --- |
| close () | Libère les ressources utilisées par cette instance. |

**Renvoie:**
void

---


### createConversation {#createConversation}

| Nom | Description |
| --- | --- |
| createConversation () | Crée une instance de conversation. Contrairement aux appels d'IA classiques, les conversations conservent le contexte complet. |

**Renvoie:**
OpenAIConversation

---