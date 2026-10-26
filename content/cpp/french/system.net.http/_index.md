---
title: "System::Net::Http"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 677
url: /fr/system.net.http/
---
## Classes

| Classe | Description |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Représente le contenu HTTP sous forme de tableau d'octets. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [Details_HttpRequestException](./details_httprequestexception/) | La classe d'exception de base est levée par les classes [HttpClient](./httpclient/) et [HttpMessageHandler](./httpmessagehandler/). Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe HttpRequestException à la place. N'enveloppez jamais les instances de la classe HttpRequestException dans [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Représente une classe de base d'un client HTTP pour envoyer des requêtes et recevoir des réponses. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpClientHandler](./httpclienthandler/) | Représente le gestionnaire de messages par défaut utilisé par la classe [HttpClient](./httpclient/). Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpContent](./httpcontent/) | Représente le contenu d'une entité HTTP. [Object](../system/object/) de cette classe doit être alloué uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpMessageHandler](./httpmessagehandler/) | Représente un type de base pour les gestionnaires de messages HTTP. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Permet aux applications d'appeler la méthode Send sur une chaîne de gestionnaires HTTP. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpMethod](./httpmethod/) | Représente une méthode HTTP. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpRequestMessage](./httprequestmessage/) | Représente un message de requête HTTP. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, comment cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpResponseMessage](./httpresponsemessage/) | Représente un message de réponse HTTP. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [HttpUtilities](./httputilities/) | Contient les méthodes utilitaires. |
| [StringContent](./stringcontent/) | Représente le contenu HTTP sous forme de chaîne. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |

## Fonctions

| Fonction | Description |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Énumérations

| Énumération | Description |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Indique quand une opération [HttpClient](./httpclient/) doit être terminée. |
| [HttpParseResult](./httpparseresult/) | Indique le résultat de l'analyse. |

## Définitions de type

| Typedef | Description |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |