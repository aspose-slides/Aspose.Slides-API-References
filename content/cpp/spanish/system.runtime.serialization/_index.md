---
title: "System::Runtime::Serialization"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 794
url: /es/system.runtime.serialization/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Representa una implementación base de la interfaz [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Proporciona la conexión entre una instancia de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) y la clase proporcionada por el formateador que mejor se adapta a analizar los datos dentro de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interfaz de objeto que puede ser serializado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y utilice este puntero para pasarlo a funciones como argumento. |
| [SerializationInfo](./serializationinfo/) | Mantiene un conjunto de campos nombrados que representan un objeto serializado. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y utilice este puntero para pasarlo a funciones como argumento. |
| [StreamingContext](./streamingcontext/) | Clase ficticia para que las clases traducidas que usan StreamingContext compilen. No administre instancias de esta clase mediante [SmartPtr](../system/smartptr/), deben asignarse solo en la pila. |
## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [SerializationException](./serializationexception/) |  |