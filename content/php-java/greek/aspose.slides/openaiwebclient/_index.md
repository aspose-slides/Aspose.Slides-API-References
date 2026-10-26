---
title: OpenAIWebClient
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/openaiwebclient/
---
## OpenAIWebClient κλάση

 Ενσωματωμένος ελαφρύς OpenAI web client

### OpenAIWebClient {#OpenAIWebClient}

| Όνομα | Περιγραφή |
| --- | --- |
| OpenAIWebClient(String, String, String) | Δημιουργεί μια παρουσία του OpenAI Web client. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |

 **Επιστρέφει:**
OpenAIWebClient

 **Σφάλμα**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Η τιμή του μοντέλου κειμένου δεν μπορεί να είναι κενή ή μηδενική |


---


### OpenAIWebClient {#OpenAIWebClient}

| Όνομα | Περιγραφή |
| --- | --- |
| OpenAIWebClient(String, String, String, HttpURLConnection) | Δημιουργεί μια παρουσία του OpenAI Web client. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| model | String | OpenAI language model. Possible values: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | String | OpenAI API key |
| organizationId | String | Organization ID (optional) |
| httpClient | HttpURLConnection | An externally managed `HttpURLConnection` instance. |

 **Επιστρέφει:**
OpenAIWebClient

 **Σφάλμα**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Η τιμή του μοντέλου κειμένου δεν μπορεί να είναι κενή ή μηδενική |


---


### callChat {#callChat}

| Όνομα | Περιγραφή |
| --- | --- |
| callChat (String) | Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας μια εξωτερικά διαχειριζόμενη παρουσία και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | String | The instruction or message to be processed by the AI model |

 **Επιστρέφει:**
String

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.OperationCanceledException | Εάν το τρέχον νήμα διακοπεί ενώ περιμένει. |


---


### close {#close}

| Όνομα | Περιγραφή |
| --- | --- |
| close () | Αποδεσμεύει τους πόρους που χρησιμοποιούνται από αυτήν την παρουσία. |

 **Επιστρέφει:**
void


---


### createConversation {#createConversation}

| Όνομα | Περιγραφή |
| --- | --- |
| createConversation () | Δημιουργεί μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν όλο το συμφραζόμενο. |

 **Επιστρέφει:**
OpenAIConversation


---