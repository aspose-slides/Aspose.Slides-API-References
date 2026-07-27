---
title: RSACryptoServiceProvider
second_title: Referencia de API de Aspose.Slides para C++
description: "Algoritmo RSA en forma CSP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a las funciones como argumento."
type: docs
weight: 469
url: /es/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider clase


[RSA](../rsa/) algoritmo en forma CSP. Los objetos de esta clase sólo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Libera todos los recursos. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | Crea una implementación predeterminada del algoritmo [RSA](../rsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | Crea una implementación predeterminada del algoritmo [RSA](../rsa/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | Crea una implementación predeterminada del algoritmo [RSA](../rsa/) con el tamaño de clave especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | Crea una implementación predeterminada del algoritmo [RSA](../rsa/) con los parámetros especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | Crea una implementación predeterminada del algoritmo [RSA](../rsa/) con parámetros codificados en XML especificados. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Descifra el mensaje. No implementado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Descifra los datos de entrada usando el modo de relleno especificado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Descifra el valor usando la clave privada. |
| void [Dispose](./dispose/)() override | Libera los datos asociados al objeto. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Encripta el mensaje. No implementado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Encripta los datos de entrada usando el modo de relleno especificado. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Encripta el valor usando la clave privada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | Exporta un blob con información sobre la clave. No implementado. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exporta los parámetros CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | Inicializa el objeto usando parámetros codificados en XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Obtiene un objeto [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Comprueba el algoritmo de intercambio de claves asociado al objeto. |
| **int32_t** [get_KeySize](./get_keysize/)() override | Obtiene el tamaño de clave usado por el algoritmo. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Obtiene una matriz de tamaños de clave permitidos. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Comprueba si la clave se persiste en el objeto CSP. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | Comprueba si solo la clave pública está presente en el objeto CSP. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtiene el algoritmo de firma asociado al objeto CSP. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Comprueba si la clave se persiste en el almacén de la máquina en lugar del de usuario. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Importa un blob con información sobre la clave. No implementado. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | Importa los parámetros CSP. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la declaración C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | Constructor. Usa parámetros predeterminados. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Constructor. No implementado. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | Constructor. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | Constructor. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Constructor. No implementado. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Establece el tamaño de la clave. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | Define si la clave se persiste en el objeto CSP. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | Define si la clave se persiste en el almacén de la máquina en lugar del de usuario. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcula la firma del valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcula la firma del valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcula la firma del valor de entrada especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo de hash y el relleno especificados, y firma el resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo de hash y el relleno especificados, y firma el resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcula el valor hash del flujo binario especificado usando el algoritmo de hash y el relleno especificados, y firma el resultado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Calcula la firma para el valor hash especificado. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Calcula la firma del valor de entrada especificado. No implementado. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | Exporta todos los parámetros en formato XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la declaración C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Comprueba la firma de los datos. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifica que la firma de los datos especificados sea válida. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifica que la firma de los datos especificados sea válida. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifica que la firma del flujo binario especificado sea válida. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Comprueba la firma de los datos. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Verifica que la firma del hash especificado sea válida. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [RSA](../rsa/)
* Clase [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Espacio de nombres [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)