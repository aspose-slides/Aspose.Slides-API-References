---
title: StreamReader()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia del objeto StreamReader que lee caracteres del flujo subyacente especificado utilizando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.
type: docs
weight: 1
url: /es/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente del que leer caracteres |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente del que leer caracteres |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del flujo, de lo contrario falso |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del flujo, de lo contrario falso |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo subyacente del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del flujo, de lo contrario falso |
| bufferSize | int | El tamaño mínimo del búfer en bytes |

## StreamReader::StreamReader(const System::String\&) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado utilizando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | La ruta del archivo del que leer caracteres |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado utilizando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | La ruta del archivo del que leer caracteres |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del archivo, de lo contrario falso |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado utilizando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | La ruta del archivo del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del flujo subyacente especificado utilizando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | La ruta del archivo del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del archivo, de lo contrario falso |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Construye una instancia del objeto [StreamReader](../) que lee caracteres del archivo especificado utilizando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si la detección de marcas de orden de bytes debe estar habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | La ruta del archivo del que leer caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a utilizar |
| detectEncodingFromByteOrderMarks | **bool** | Verdadero para buscar marcas de orden de bytes al inicio del archivo, de lo contrario falso |
| bufferSize | int | El tamaño mínimo del búfer en bytes |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)