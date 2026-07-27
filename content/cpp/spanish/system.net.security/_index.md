---
title: "System::Net::Security"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 716
url: /es/system.net.security/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que producirá errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use dicho puntero para pasarlo a funciones como argumento. |
| [SslStream](./sslstream/) | Un flujo que usa el protocolo SSL para autenticar el servidor y opcionalmente el cliente. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Indicadores de autenticación específicos de WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumera los errores de política de SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumera las políticas de cifrado. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Un delegado de usuario utilizado para verificar el certificado SSL remoto. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Un delegado de usuario utilizado para seleccionar el certificado SSL local. |