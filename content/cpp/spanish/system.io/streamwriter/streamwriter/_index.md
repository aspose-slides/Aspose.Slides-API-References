---
title: StreamWriter()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia del objeto StreamWriter que escribe caracteres en el flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.
type: docs
weight: 1
url: /es/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente al que se escribirán los caracteres |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente al que se escribirán los caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a usar |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si el flujo subyacente debe cerrarse cuando el objeto [StreamWriter](../) se elimina.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente al que se escribirán los caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a usar |
| buffer_size | int | El tamaño mínimo del búfer en bytes |
| leave_open | **bool** | Indica si el flujo subyacente debe permanecer abierto después de que el objeto [StreamWriter](../) actual se elimine |

## StreamWriter::StreamWriter(const String\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo al que se escribirán los caracteres |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo al que se escribirán los caracteres |
| append | **bool** | Indica si los datos deben añadirse al archivo especificado (true) o si el archivo debe sobrescribirse (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a usar |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor


Construye una instancia del objeto [StreamWriter](../) que escribe caracteres en el archivo especificado usando la codificación especificada y el tamaño de búfer indicado. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | La ruta del archivo al que se escribirán los caracteres |
| append | **bool** | Indica si los datos deben añadirse al archivo especificado (true) o si el archivo debe sobrescribirse (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a usar |
| buffer_size | int | El tamaño del búfer a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [Stream](../../stream/)
* Clase [StreamWriter](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)