---
title: Details_SoapException
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa la excepción lanzada cuando se llama a un método a través de SOAP y se produce un error. Nunca cree instancias de esta clase manualmente. Utilice la clase SoapException en su lugar. Nunca envuelva las instancias de la clase SoapException en System::SmartPtr."
type: docs
weight: 1
url: /es/system.web.services.protocols/details_soapexception/
---
## Details_SoapException clase


Representa la excepción lanzada cuando se llama a un método a través de SOAP y se produce un error. Nunca cree instancias de esta clase manualmente. Utilice la SoapException clase en su lugar. Nunca envuelva las instancias de la SoapException clase dentro de [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_SoapException : public System::Details_SystemException
```

## Métodos

| Method | Description |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Construye una nueva instancia. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Construye una nueva instancia. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | Devuelve la pieza de código donde se lanza la excepción cuando se usa la versión 1.1 de SOAP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | Devuelve un nombre local calificado por espacio de nombres en formato 'namespace:localname' que especifica el código de error SOAP. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Devuelve un diccionario con datos personalizados de la excepción. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | Devuelve detalles sobre la excepción lanzada. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Devuelve un valor entero de 32 bits que es un código HRESULT asociado con la excepción representada por el objeto actual. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Devuelve una referencia al objeto que representa la excepción interna. |
| [String](../../system/string/) [get_Lang](./get_lang/)() | Devuelve el idioma que se utiliza para localizar las propiedades de la excepción. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Devuelve la cadena que contiene la descripción del error. |
| [String](../../system/string/) [get_Node](./get_node/)() | Devuelve la pieza de código donde se lanza la excepción cuando se usa la versión 1.2 de SOAP. |
| [String](../../system/string/) [get_Role](./get_role/)() | Devuelve el rol del servicio web XML que lanza la excepción. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Devuelve la cadena que contiene la traza de la pila. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | Devuelve información opcional del elemento XML 'subcode'. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Devuelve una copia del objeto Exception que representa la excepción más interna. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Comprueba si el código especificado es igual al código de error SOAP 'Client'. |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Comprueba si el código especificado es igual al código de error SOAP 'MustUnderstand'. |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Comprueba si el código especificado es igual al código de error SOAP 'Server'. |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Comprueba si el código especificado es igual al código de error SOAP 'VersionMismatch'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Establece HRESULT, un valor numérico codificado que se asigna a una excepción específica. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Devuelve la representación en cadena del objeto actual. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementa el método [what()](../../system/details_exception/what/) que es llamado por la clase [ExceptionWrapper](../../system/exceptionwrapper/). A pesar de que esta clase no hereda de std::exception, las clases derivadas pueden usar miembros protegidos/privados para implementar su lógica. Mover la implementación de este método al [ExceptionWrapper](../../system/exceptionwrapper/) podría romper esa lógica. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Campos

| Field | Description |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | Un código de error SOAP que representa una llamada del cliente formateada incorrectamente o que no contiene la información requerida. |
| static [DetailElementName](./detailelementname/) | Un nombre local calificado por espacio de nombres en formato 'namespace:localname'. |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | Un código de error SOAP que indica que el elemento SOAP marcado con el atributo 'MustUnderstand' no se procesa. |
| static [ServerFaultCode](./serverfaultcode/) | Un código de error SOAP que representa un error ocurrido en el servidor. |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | Un código de error SOAP que representa un espacio de nombres inválido. |

## Ver también

* Clase [Details_SystemException](../../system/details_systemexception/)
* Espacio de nombres [System::Web::Services::Protocols](../)
* Biblioteca [Aspose.Slides](../../)