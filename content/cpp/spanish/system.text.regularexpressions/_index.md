---
title: "System::Text::RegularExpressions"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 989
url: /es/system.text.regularexpressions/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Capture](./capture/) | Resultado de la coincidencia de una subexpresión única. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [CaptureCollection](./capturecollection/) | Lista de capturas realizadas por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Group](./group/) | Resultado de la coincidencia realizada por un único grupo de captura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [GroupCollection](./groupcollection/) | Lista de grupos de captura en una única coincidencia. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [GroupCollectionPtr](./groupcollectionptr/) | Puntero de colección [Group](./group/). Este tipo es un puntero para gestionar la eliminación de otros objetos. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante. |
| [Match](./match/) | Coincidencia [Single](../system/single/) de expresión regular sobre cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MatchCollection](./matchcollection/) | Colección de coincidencias realizadas aplicando repetidamente la expresión regular a una cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Regex](./regex/) | Expresión regular que sigue una sintaxis similar a C#. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando operator new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |

## Funciones

| Función | Descripción |
| --- | --- |
| [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Envoltorio para mantener la clase MatchHolder sin su inclusión, así como PCRE2. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [RegexOptions](./regexoptions/) | Opciones [Regex](./regex/). |

## Tipos definidos

| Typedef | Descripción |
| --- | --- |
| [UStringPtr](./ustringptr/) | UnicodeString compartido para evitar copias. |
| [CapturePtr](./captureptr/) | Puntero a objeto de captura único. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Puntero a colección de capturas. |
| [GroupPtr](./groupptr/) | Puntero a grupo. |
| [RegexPtr](./regexptr/) | Puntero [Regex](./regex/). |
| [MatchPtr](./matchptr/) | Puntero [Match](./match/). |
| [MatchCollectionPtr](./matchcollectionptr/) | Puntero a colección [Match](./match/). |
| [MatchEvaluator](./matchevaluator/) | Tipo de delegado para evaluar la coincidencia. |