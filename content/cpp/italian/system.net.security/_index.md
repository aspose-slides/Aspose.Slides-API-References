---
title: "System::Net::Security"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 716
url: /it/system.net.security/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contiene i metodi per passare le credenziali attraverso un flusso. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [SslStream](./sslstream/) | Un flusso che utilizza il protocollo SSL per autenticare il server e, facoltativamente, il client. |
## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Flag di autenticazione specifici per WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Elenca gli errori di politica di SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Elenca le politiche di crittografia. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Un delegato utente utilizzato per verificare il certificato SSL remoto. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Un delegato utente utilizzato per selezionare il certificato SSL locale. |