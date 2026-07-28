---
title: "System::Net::Security"
second_title: Aspose.Slides dla C++ odwołanie API
description: 
type: docs
weight: 716
url: /pl/system.net.security/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Zawiera metody do przekazywania poświadczeń przez strumień. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operator new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze owiń tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika, aby przekazać ją do funkcji jako argument. |
| [SslStream](./sslstream/) | Strumień używający protokołu SSL do uwierzytelniania serwera i opcjonalnie klienta. |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Flagi uwierzytelniania specyficzne dla WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Wylicza błędy polityki SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Wylicza zasady szyfrowania. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Delegat użytkownika używany do weryfikacji zdalnego certyfikatu SSL. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Delegat użytkownika używany do wyboru lokalnego certyfikatu SSL. |