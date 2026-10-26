---
title: "System::Net::Security"
second_title: "Aspose.Slides для C++ Справочник API"
description: 
type: docs
weight: 716
url: /ru/system.net.security/
---
## Классы

| Класс | Описание |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Содержит методы для передачи учётных данных через поток. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [SslStream](./sslstream/) | Поток, использующий протокол SSL для аутентификации сервера и, при необходимости, клиента. |
## Перечисления

| Перечисление | Описание |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Флаги аутентификации, специфичные для WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Перечисляет ошибки политики SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Перечисляет политики шифрования. |
## Типы

| Тип | Описание |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Пользовательский делегат, используемый для проверки удалённого SSL-сертификата. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Пользовательский делегат, используемый для выбора локального SSL-сертификата. |