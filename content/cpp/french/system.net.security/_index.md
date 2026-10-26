---
title: "System::Net::Security"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 716
url: /fr/system.net.security/
---
## Classes

| Classe | Description |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contient les méthodes permettant de transmettre les informations d’identification à travers un flux. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument. |
| [SslStream](./sslstream/) | Un flux qui utilise le protocole SSL pour authentifier le serveur et éventuellement le client. |
## Énumérations

| Énum | Description |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Indicateurs d’authentification spécifiques à WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Énumère les erreurs de politique de SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Énumère les politiques de chiffrement. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Un délégué utilisateur utilisé pour vérifier le certificat SSL distant. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Un délégué utilisateur utilisé pour sélectionner le certificat SSL local. |