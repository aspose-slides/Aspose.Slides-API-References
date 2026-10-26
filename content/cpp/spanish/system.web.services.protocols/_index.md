---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides para la referencia de la API de C++
description: 
type: docs
weight: 1080
url: /es/system.web.services.protocols/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Representa la excepción lanzada cuando se llama al método a través de SOAP y ocurre un error. Nunca cree instancias de esta clase manualmente. Use la clase SoapException en su lugar. Nunca envuelva las instancias de la clase SoapException dentro de [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Esta clase base se usa en todos los proxies de cliente de servicio XML [Web](../system.web/) que utilizan HTTP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Una instancia de esta clase se pasa como argumento al delegado InvokeCompletedEventHandler. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapClientMessage](./soapclientmessage/) | Representa los datos en una solicitud SOAP enviada o una respuesta SOAP recibida. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Especifica que todos los mensajes SOAP pasados o devueltos por el método usan el formato Document. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Establece el formato predeterminado para las solicitudes y respuestas SOAP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapHeader](./soapheader/) | Representa el contenido del encabezado SOAP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Especifica el encabezado SOAP que el método de servicio XML [Web](../system.web/) o el cliente de servicio XML [Web](../system.web/) pueden procesar. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapHeaderCollection](./soapheadercollection/) | Contiene una colección de instancias de la clase [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Los servicios de proxy de cliente deben heredar esta clase cuando se usa SOAP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [SoapMessage](./soapmessage/) | Representa el mensaje SOAP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |
| [WebClientProtocol](./webclientprotocol/) | Esta clase base se usa en todos los proxies de cliente de servicio XML [Web](../system.web/) que fueron creados usando ASP.NET. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use este puntero para pasarlo a funciones como argumento. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Enumera las direcciones de los encabezados SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Enumera las etapas de procesamiento de los mensajes SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Enumera los formatos de parámetros en un mensaje SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Enumera las versiones de SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Enumera las opciones de cómo se enruta un mensaje SOAP al servicio XML [Web](../system.web/). |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [SoapException](./soapexception/) |  |