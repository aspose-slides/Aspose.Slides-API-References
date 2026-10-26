---
title: Uri
second_title: Referencia de la API de Aspose.Slides para C++
description: "Identificador de recurso uniforme. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 1392
url: /es/system/uri/
---
## Clase Uri

Identificador de recurso uniforme. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Uri : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Determina el tipo del nombre de host especificado. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Determina si el esquema especificado es válido. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Compara los objetos [Uri](./) especificados usando las reglas de comparación especificadas. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Determina si los URI representados por el objeto actual y el objeto especificado son iguales. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Convierte una cadena a su representación con escape. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Convierte una cadena URI a su representación con escape. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Obtiene el valor decimal de un dígito hexadecimal. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Devuelve la ruta absoluta del URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Devuelve el URI absoluto. |
| [String](../string/) [get_Authority](./get_authority/)() const | Devuelve el nombre del host y el número de puerto de un servidor. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Devuelve un nombre de host sin escape. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Devuelve el fragmento del URI con escape. |
| [String](../string/) [get_Host](./get_host/)() const | Devuelve el nombre del host. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Devuelve el tipo de nombre del host. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Devuelve un Nombre de Dominio Internacional del host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determina si el URI representado por el objeto actual es absoluto. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Determina si el URI representado por el objeto actual tiene el puerto predeterminado para el esquema del URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Determina si el URI representado por el objeto actual es un archivo. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Determina si el URI representado por el objeto actual hace referencia a un host local. |
| **bool** [get_IsUnc](./get_isunc/)() const | Determina si el URI representado por el objeto actual es una ruta UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Devuelve la representación del sistema operativo del nombre de archivo referenciado por el URI representado por el objeto actual. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Devuelve la cadena URI que se pasó al constructor cuando se construyó el objeto actual. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Devuelve la ruta absoluta y los componentes de consulta del URI representado por el objeto actual, separados por un signo de interrogación (?). |
| **int32_t** [get_Port](./get_port/)() const | Devuelve el número de puerto del URI representado por el objeto actual. |
| [String](../string/) [get_Query](./get_query/)() const | Devuelve la información de consulta incluida en el URI representado por el objeto actual. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Devuelve el esquema del URI representado por el objeto actual. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Devuelve una matriz de cadenas que contiene los segmentos de ruta del URI representado por el objeto actual. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Determina si la cadena URI pasada al constructor del objeto actual estaba completamente escapada. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Devuelve el nombre de usuario, la contraseña y otra información de usuario asociada al URI representado por el objeto actual. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Devuelve los componentes especificados del URI representado por el objeto actual usando el escape especificado. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Obtiene el código hash del URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Devuelve la porción especificada del URI representado por el objeto actual. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Devuelve el equivalente hexadecimal del carácter especificado. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Convierte la representación hexadecimal especificada de un carácter a un carácter. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Determina si el URI representado por el objeto [Uri](./) actual es la base del URI representado por el objeto [Uri](./) especificado. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Determina si el carácter especificado representa un dígito hexadecimal válido. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Determina si un carácter en la cadena especificada en la posición especificada está codificado en hexadecimal. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indica si la cadena utilizada para construir este [Uri](./) estaba bien formada y no requiere ser escapada más. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Determina si la cadena especificada es un URI bien formado. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina la diferencia entre dos instancias de [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina la diferencia entre los URI representados por el objeto actual y los objetos [Uri](./) especificados. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Devuelve la representación en cadena del URI representado por el objeto actual. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento especifica el tipo de URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construye un objeto [Uri](./) a partir del objeto [Uri](./) especificado que representa el URI base y la representación en cadena del URI relativo. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construye un objeto [Uri](./) a partir de los URI base y relativo especificados. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Desescapa la cadena escapada especificada. |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Construye un objeto [Uri](./) que representa el URI especificado. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento especifica si el URI debe escaparse. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Construye un objeto [Uri](./) a partir del objeto [Uri](./) especificado que representa el URI base y la representación en cadena del URI relativo; un argumento especifica si el URI debe escaparse. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento especifica el tipo de URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Construye un objeto [Uri](./) a partir de los URI base y relativo especificados. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construye un objeto [Uri](./) a partir de los URI base y relativo especificados. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Especifica los caracteres que separan el esquema del protocolo de comunicación de la parte de dirección del [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Especifica que el [Uri](./) es un puntero a un archivo. |
| static [UriSchemeFtp](./urischemeftp/) | Especifica que el [Uri](./) se accede a través del Protocolo de Transferencia de Archivos. |
| static [UriSchemeGopher](./urischemegopher/) | Especifica que el [Uri](./) se accede a través del protocolo Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Especifica que el [Uri](./) se accede a través del Protocolo de Transferencia de Hipertexto. |
| static [UriSchemeHttps](./urischemehttps/) | Especifica que el [Uri](./) se accede a través del Protocolo Seguro de Transferencia de Hipertexto. |
| static [UriSchemeMailto](./urischememailto/) | Especifica que el [Uri](./) es una dirección de correo electrónico y se accede a través del Protocolo Simple de Transporte de Correo. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Especifica que el [Uri](./) se accede a través del esquema NetPipe usado por [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Especifica que el [Uri](./) se accede a través del esquema NetTcp usado por [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Especifica que el [Uri](./) es un grupo de noticias de Internet y se accede a través del Protocolo de Transporte de Noticias de Red. |
| static [UriSchemeNntp](./urischemenntp/) | Especifica que el [Uri](./) es un grupo de noticias de Internet y se accede a través del Protocolo de Transporte de Noticias de Red. |

## Observaciones

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Véase también

* Clase [Object](../object/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)