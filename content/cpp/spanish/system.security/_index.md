---
title: "System::Security"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 807
url: /es/system.security/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Cadena segura, representa texto que debe mantenerse confidencial. Esta clase NO ENCRIPTA los datos internos. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a funciones como argumento. |
| [SecureStringMarshal](./securestringmarshal/) | Colección de métodos para asignar y copiar bloques de memoria no administrada. |
| [SecurityElement](./securityelement/) | Modelo de objeto XML para codificar objeto de seguridad. No implementado. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarla a funciones como argumento. |

## Definiciones de tipos

| Typedef | Descripción |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | Tipo de puntero [SecureString](./securestring/). |