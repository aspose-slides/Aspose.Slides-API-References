---
title: X500DistinguishedName
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa el nombre distinguido de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 14
url: /es/system.security.cryptography.x509certificates/x500distinguishedname/
---
## X500DistinguishedName clase


Representa el nombre distinguido de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y utilice ese puntero para pasarlo a funciones como argumento.

```cpp
class X500DistinguishedName : public System::Security::Cryptography::AsnEncodedData
```

## Métodos

| Method | Description |
| --- | --- |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | Constructor de copia. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
| virtual void [CopyFrom](../../system.security.cryptography/asnencodeddata/copyfrom/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | Copia datos de otro objeto. |
| [String](../../system/string/) [Decode](./decode/)([X500DistinguishedNameFlags](../x500distinguishednameflags/)) const | Decodifica el nombre usando los parámetros especificados por las banderas. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales, aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales, aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [String](../../system/string/) [Format](./format/)(**bool**) const override | Formatea el nombre para imprimir. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtiene el nombre distinguido del certificado. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_Oid](../../system.security.cryptography/asnencodeddata/get_oid/)() const | Obtiene el identificador de objeto de los datos codificados. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](../../system.security.cryptography/asnencodeddata/get_rawdata/)() const | Obtiene los datos codificados crudos. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Oid](../../system.security.cryptography/asnencodeddata/set_oid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&) | Establece el identificador de objeto de los datos codificados. |
| void [set_RawData](../../system.security.cryptography/asnencodeddata/set_rawdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Establece los datos codificados crudos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [X500DistinguishedName](./x500distinguishedname/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | Constructor. |
|  [X500DistinguishedName](./x500distinguishedname/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X500DistinguishedName](./x500distinguishedname/)(const [String](../../system/string/)\&) | Constructor. |
|  [X500DistinguishedName](./x500distinguishedname/)(const [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](./)\>\&) | Constructor de copia. |
|  [X500DistinguishedName](./x500distinguishedname/)(const [String](../../system/string/)\&, [X500DistinguishedNameFlags](../x500distinguishednameflags/)) | Constructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)