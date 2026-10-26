---
title: "System::Net::Http"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 677
url: /es/system.net.http/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Representa contenido HTTP como una matriz de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Details_HttpRequestException](./details_httprequestexception/) | La clase base de excepción es lanzada por las clases [HttpClient](./httpclient/) y [HttpMessageHandler](./httpmessagehandler/). Nunca cree instancias de esta clase manualmente. Use la clase HttpRequestException en su lugar. Nunca envuelva las instancias de la clase HttpRequestException en [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Representa una clase base de un cliente HTTP para enviar solicitudes y recibir respuestas. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpClientHandler](./httpclienthandler/) | Representa el manejador de mensajes predeterminado usado por la clase [HttpClient](./httpclient/). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpContent](./httpcontent/) | Representa el contenido de una entidad HTTP. [Object](../system/object/) de esta clase solo debe asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpMessageHandler](./httpmessagehandler/) | Representa un tipo base para los manejadores de mensajes HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Permite a las aplicaciones llamar al método Send en una cadena de manejadores HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpMethod](./httpmethod/) | Representa un método HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpRequestMessage](./httprequestmessage/) | Representa un mensaje de solicitud HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpResponseMessage](./httpresponsemessage/) | Representa un mensaje de respuesta HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [HttpUtilities](./httputilities/) | Contiene los métodos de utilidad. |
| [StringContent](./stringcontent/) | Representa contenido HTTP como una cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
## Funciones

| Función | Descripción |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Indica cuándo debe completarse una operación [HttpClient](./httpclient/). |
| [HttpParseResult](./httpparseresult/) | Indica el resultado del análisis. |
## Tipos definidos

| Tipo definido | Descripción |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |