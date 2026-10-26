---
title: FileInfo
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa una ruta a un archivo y el archivo referido por esa ruta y proporciona métodos para manipularlo. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 274
url: /es/system.io/fileinfo/
---
## FileInfo clase

Representa una ruta a un archivo y el archivo referido por esa ruta, y proporciona métodos para manipularlo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Abre un archivo representado por el objeto actual para escribir texto usando codificación UTF-8, en modo 'Append' sin uso compartido. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Copia el archivo representado por el objeto actual a la ubicación especificada. Si el archivo de destino ya existe, la copia falla. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Copia el archivo representado por el objeto actual a la ubicación especificada. Un parámetro indica si el archivo de destino existente debe sobrescribirse. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Crea un archivo en la ubicación especificada por la ruta representada por el objeto actual y lo abre para lectura y escritura, en modo de truncado y sin uso compartido. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Crea un archivo en la ubicación especificada por la ruta representada por el objeto actual y lo abre para escribir texto usando codificación UTF-8 sin uso compartido. |
| void [Decrypt](./decrypt/)() | NO IMPLEMENTADO. |
| void [Delete](./delete/)() override | Elimina el archivo representado por el objeto actual. |
| void [Encrypt](./encrypt/)() | NO IMPLEMENTADO. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para fines internos. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Construye una nueva instancia de la clase [FileInfo](./) que representa el archivo especificado. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | No hace nada. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Devuelve los atributos de la entidad representada por el objeto actual. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Devuelve la hora de creación de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Devuelve la hora de creación de la entidad representada por el objeto actual en hora UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Devuelve un objeto [DirectoryInfo](../directoryinfo/) que representa el directorio en el que se encuentra el archivo representado por el objeto actual. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Devuelve el nombre completo del directorio en el que se encuentra el archivo representado por el objeto actual. |
| **bool** [get_Exists](./get_exists/)() override | Devuelve un valor que indica si el archivo existe. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Devuelve la extensión del archivo representado por el objeto actual. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Devuelve el nombre completo (incluyendo la ruta) de la entidad representada por el objeto actual. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Devuelve un valor que indica si el atributo ReadOnly está establecido. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Devuelve la última hora de acceso de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Devuelve la última hora de acceso de la entidad representada por el objeto actual en hora UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Devuelve la última hora de escritura de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Devuelve la última hora de escritura de la entidad representada por el objeto actual en hora UTC. |
| **int64_t** [get_Length](./get_length/)() | Devuelve el tamaño del archivo en bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Devuelve el nombre del archivo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Mueve el archivo representado por el objeto actual a la ubicación especificada. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Abre el archivo representado por el objeto actual en el modo especificado para lectura y escritura sin uso compartido. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y sin uso compartido. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Abre el archivo representado por el objeto actual en el modo especificado, con el tipo de acceso especificado y la opción de uso compartido. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Abre un archivo representado por el objeto actual solo para lectura, en modo 'Open' con acceso compartido para lectura. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Abre el archivo existente en la ubicación especificada por la ruta representada por el objeto actual para leer texto usando codificación UTF-8 sin uso compartido. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Abre un archivo representado por el objeto actual solo para escritura, en modo 'OpenOrCreate' sin uso compartido. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| void [Refresh](../filesysteminfo/refresh/)() | Actualiza el estado del objeto actual. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](./) actual y crea una copia de seguridad del archivo reemplazado. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Reemplaza el contenido de un archivo de destino especificado con el archivo representado por el objeto [FileInfo](./) actual y crea una copia de seguridad del archivo reemplazado. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Establece los atributos especificados en la entidad representada por el objeto actual. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad representada por el objeto actual en hora local. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad representada por el objeto actual en hora UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Establece o elimina el atributo ReadOnly del archivo. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad representada por el objeto actual en hora local. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad representada por el objeto actual en hora UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad representada por el objeto actual en hora local. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad representada por el objeto actual en hora UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Devuelve una ruta representada por el objeto actual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [FileSystemInfo](../filesysteminfo/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)