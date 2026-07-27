---
title: File
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona métodos para manipular archivos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 261
url: /es/system.io/file/
---
## File clase


Proporciona métodos para manipular archivos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class File
```

## Métodos

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Agrega cadenas de la colección especificada de cadenas al archivo especificado usando la codificación especificada, escribiendo cada cadena en una nueva línea. Si el archivo especificado no existe, se crea. El archivo se cierra después de escribir todas las cadenas. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Agrega la cadena especificada al archivo especificado usando la codificación especificada. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Crea un objeto [StreamWriter](../streamwriter/) que agrega texto al archivo especificado usando codificación UTF-8. Si el archivo especificado no existe, se crea. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Copia el archivo especificado a la ubicación especificada. Si el archivo de destino ya existe, un parámetro indica si debe sobrescribirse. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Crea un archivo nuevo (o sobrescribe el existente) y lo abre para acceso de lectura y escritura usando el tamaño de búfer y las opciones especificados. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Crea un nuevo archivo o abre el existente para escribir texto codificado en UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NO IMPLEMENTADO. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Elimina el archivo o directorio especificado. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NO IMPLEMENTADO. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Determina si la ruta especificada hace referencia a un archivo existente. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Devuelve los atributos de la entidad especificada. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Devuelve la hora de creación de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Devuelve la hora de creación de la entidad especificada en tiempo UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Devuelve la hora de último acceso de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Devuelve la hora de último acceso de la entidad especificada en tiempo UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Devuelve la hora de última escritura de la entidad especificada en hora local. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Devuelve la hora de última escritura de la entidad especificada en tiempo UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Mueve el archivo especificado a la nueva ubicación. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Abre el archivo especificado en el modo especificado para lectura y escritura sin uso compartido. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Abre el archivo especificado en el modo especificado, con el tipo de acceso y opción de uso compartido especificados. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Abre el archivo especificado solo para lectura, en modo 'Open' con acceso compartido para lectura. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Abre el archivo existente especificado para leer texto usando codificación UTF-8 sin uso compartido. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Abre el archivo especificado solo para escritura, en modo 'OpenOrCreate' sin uso compartido. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Lee el contenido del archivo binario especificado a una matriz de bytes. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lee el contenido del archivo de texto especificado línea por línea a una matriz de cadenas usando la codificación de caracteres especificada. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lee el contenido del archivo de texto especificado a un único objeto [String](../../system/string/) usando la codificación de caracteres especificada. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lee el contenido del archivo de texto especificado línea por línea usando la codificación de caracteres especificada y devuelve una colección enumerable de cadenas, cada una de las cuales representa una línea única del contenido del archivo. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Reemplaza el contenido de un archivo con otro y crea una copia de seguridad del archivo reemplazado. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Establece los atributos especificados en el archivo especificado. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NO IMPLEMENTADO. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NO IMPLEMENTADO. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NO IMPLEMENTADO. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NO IMPLEMENTADO. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la hora de última escritura de la entidad especificada en hora local. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Establece la hora de última escritura de la entidad especificada en tiempo UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Sobrescribe el archivo binario especificado y escribe los bytes especificados en él. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un archivo de texto nuevo o sobrescribe el existente y escribe todas las cadenas de la colección enumerable especificada en él, cada cadena en una nueva línea, usando la codificación especificada. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un archivo de texto nuevo o sobrescribe el existente y escribe todas las cadenas del array especificado en él, cada cadena en una nueva línea, usando la codificación especificada. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crea un archivo de texto nuevo o sobrescribe el existente y escribe el contenido de la cadena especificada en él usando la codificación especificada. |
## Campos

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valor predeterminado del número de bytes almacenados en búfer durante la lectura y escritura de un archivo. |
## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)