---
title: DirectoryInfo
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa una ruta del sistema de archivos, un directorio al que se refiere dicha ruta y proporciona métodos de instancia para manipular directorios. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento."
type: docs
weight: 248
url: /es/system.io/directoryinfo/
---
## DirectoryInfo clase

Representa una ruta del sistema de archivos, un directorio al que se refiere esta ruta y proporciona métodos de instancia para manipular directorios. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Create](./create/)() | Crea un directorio en la ruta representada por el objeto actual. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Crea subdirectorios en la ruta especificada. |
| void [Delete](./delete/)() override | Elimina el directorio al que se refiere la ruta representada por el objeto actual si el directorio está vacío. |
| void [Delete](./delete/)(**bool**) | Elimina el directorio al que se refiere la ruta representada por el objeto actual. Un parámetro especifica si el contenido del directorio debe eliminarse recursivamente cuando el directorio no está vacío. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Construye una instancia de la clase [DirectoryInfo](./) en la ruta especificada. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Devuelve una colección enumerable que contiene todos los directorios ubicados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Busca los directorios que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Devuelve una colección enumerable que contiene todos los archivos ubicados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Busca los archivos que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Devuelve una colección enumerable que contiene todos los archivos y directorios ubicados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | No hace nada. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Devuelve los atributos de la entidad representada por el objeto actual. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Devuelve la hora de creación de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Devuelve la hora de creación de la entidad representada por el objeto actual en hora UTC. |
| **bool** [get_Exists](./get_exists/)() override | Determina si la ruta representada por el objeto actual hace referencia a un directorio existente. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Devuelve la extensión del archivo representado por el objeto actual. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Devuelve el nombre completo (incluyendo ruta) de la entidad representada por el objeto actual. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Devuelve la última hora de acceso de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Devuelve la última hora de acceso de la entidad representada por el objeto actual en hora UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Devuelve la última hora de escritura de la entidad representada por el objeto actual en hora local. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Devuelve la última hora de escritura de la entidad representada por el objeto actual en hora UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Devuelve el nombre de la entidad a la que se refiere la ruta representada por el objeto actual. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Devuelve un puntero compartido al objeto [DirectoryInfo](./) que representa una ruta que hace referencia al directorio padre del directorio representado por el objeto actual. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Devuelve un puntero compartido al objeto [DirectoryInfo](./) que representa una ruta que hace referencia al directorio raíz del directorio representado por el objeto actual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Devuelve una matriz que contiene punteros compartidos a objetos [DirectoryInfo](./) que representan todos los directorios ubicados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Busca los directorios que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Devuelve una matriz que contiene punteros compartidos a objetos [FileInfo](../fileinfo/) que representan todos los directorios ubicados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Busca los archivos que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Devuelve una matriz que contiene punteros compartidos a objetos [FileSystemInfo](../filesysteminfo/) que representan todos los archivos y directorios ubicados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados en el directorio representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Busca los archivos y directorios que cumplen los criterios de búsqueda especificados, ya sea en el directorio representado por el objeto actual o en todo el árbol de directorios cuya raíz es el directorio representado por el objeto actual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Mueve el directorio representado por el objeto actual y todo su contenido a la ubicación especificada. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| void [Refresh](../filesysteminfo/refresh/)() | Actualiza el estado del objeto actual. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Establece los atributos especificados en la entidad representada por el objeto actual. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad representada por el objeto actual en hora local. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Establece la hora de creación de la entidad representada por el objeto actual en hora UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad representada por el objeto actual en hora local. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Establece la última hora de acceso de la entidad representada por el objeto actual en hora UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad representada por el objeto actual en hora local. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Establece la última hora de escritura de la entidad representada por el objeto actual en hora UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el enésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Devuelve una cadena que contiene la ruta representada por el objeto actual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [FileSystemInfo](../filesysteminfo/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)