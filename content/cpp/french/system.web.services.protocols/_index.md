---
title: "System::Web::Services::Protocols"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 1080
url: /fr/system.web.services.protocols/
---
## Classes

| Class | Description |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Représente l'exception levée lorsqu'une méthode est appelée via SOAP et qu'une erreur se produit. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe SoapException à la place. Ne encapsulez jamais les instances de la classe SoapException dans [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Cette classe de base est utilisée dans tous les proxies client de service XML [Web](../system.web/) qui utilisent HTTP. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Une instance de cette classe est transmise comme argument au délégué InvokeCompletedEventHandler. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapClientMessage](./soapclientmessage/) | Représente les données d'une requête SOAP envoyée ou d'une réponse SOAP reçue. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Spécifie que tous les messages SOAP transmis ou renvoyés par la méthode utilisent le format Document. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Définit le format par défaut pour les requêtes et réponses SOAP. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapHeader](./soapheader/) | Représente le contenu de l'en-tête SOAP. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Spécifie l'en-tête SOAP que la méthode de service XML [Web](../system.web/) ou le client de service XML [Web](../system.web/) peut traiter. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapHeaderCollection](./soapheadercollection/) | Contient une collection d'instances de la classe [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Les services de proxy client doivent hériter de cette classe lorsque SOAP est utilisé. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SoapMessage](./soapmessage/) | Représente le message SOAP. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [WebClientProtocol](./webclientprotocol/) | Cette classe de base est utilisée dans tous les proxies client de service XML [Web](../system.web/) qui ont été créés avec ASP.NET. Les objets de cette classe ne doivent être alloués qu'avec la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
## Énumérations

| Enum | Description |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Énumère les directions d'en-tête SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Énumère les étapes de traitement des messages SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Énumère les formats de paramètres dans un message SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Énumère les versions de SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Énumère les options de façon dont un message SOAP est routé vers le service XML [Web](../system.web/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SoapException](./soapexception/) |  |