---
title: Cookie
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa una cookie HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 1
url: /es/system.net/cookie/
---
## Cookie clase


Representa una cookie HTTP. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Cookie : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Crea una copia de la instancia actual. |
| [Cookie](./cookie/)() | Construye una nueva instancia. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Construye una nueva instancia. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construye una nueva instancia. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construye una nueva instancia. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Obtiene el valor del atributo 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Obtiene el valor del atributo 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Obtiene el valor del atributo 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Obtiene el valor del atributo 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Obtiene un valor que indica si el dominio es implícito. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Devuelve la clave del dominio. |
| **bool** [get_Expired](./get_expired/)() | Obtiene un valor que indica si la cookie ha expirado. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Obtiene el valor del atributo 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Obtiene el valor del atributo 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtiene el nombre de la cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Obtiene el valor del atributo 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Devuelve un valor que indica si la especificación de la cookie es 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Obtiene el valor del atributo 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Devuelve la colección de valores del atributo 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Obtiene el valor del atributo 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Devuelve la hora en que se creó la cookie. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Obtiene el valor de la cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Obtiene la especificación de la cookie. |
| **int32_t** [get_Version](./get_version/)() const | Obtiene el valor del atributo '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Este método es llamado por otros métodos para establecer un nombre de método. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Establece el valor del atributo 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Establece el valor del atributo 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Establece el valor del atributo 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Establece el valor del atributo 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Establece un valor que indica si el dominio es implícito. |
| void [set_Expired](./set_expired/)(**bool**) | Establece un valor que indica si la cookie ha expirado. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Establece el valor del atributo 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Establece el valor del atributo 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Establece el nombre de la cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Establece el valor del atributo 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Establece el valor del atributo 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Establece el valor del atributo 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Establece el valor de la cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Establece la especificación de la cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Establece el valor del atributo '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializa la instancia actual a su representación en cadena. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifica y establece los valores predeterminados de los atributos. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | El nombre del atributo 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | El nombre del atributo 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | El nombre del atributo 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | El nombre del atributo 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | El separador usado para separar el nombre y el valor de un atributo. |
| static [ExpiresAttributeName](./expiresattributename/) | El nombre del atributo 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | El nombre del atributo 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | El nombre del atributo 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | La versión máxima soportada. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | La representación en cadena de la versión máxima soportada. |
| static [PathAttributeName](./pathattributename/) | El nombre del atributo 'Path'. |
| static [PortAttributeName](./portattributename/) | El nombre del atributo 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | El arreglo que contiene delimitadores para los valores del atributo 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | El símbolo usado para envolver las partes del atributo. |
| static [ReservedToName](./reservedtoname/) | Un valor reservado para el nombre de la cookie. |
| static [ReservedToValue](./reservedtovalue/) | Un valor reservado para el valor de la cookie. |
| static [SecureAttributeName](./secureattributename/) | El nombre del atributo 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | El separador de atributos. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | El prefijo de los nombres de los atributos especiales. |
| static [VersionAttributeName](./versionattributename/) | El nombre del atributo '[Version](../../system/version/)'. |

## Véase también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Net](../)
* Biblioteca [Aspose.Slides](../../)