---
title: StreamReader()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy instancję obiektu StreamReader, który odczytuje znaki z określonego podstawowego strumienia przy użyciu kodowania UTF-8 oraz bufora o domyślnym rozmiarze 1024 bajtów.
type: docs
weight: 1
url: /pl/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu kodowania UTF-8 oraz bufora o domyślnym rozmiarze 1024 bajtów.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy strumień, z którego odczytywane są znaki |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu kodowania UTF-8 oraz bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy strumień, z którego odczytywane są znaki |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku strumienia, w przeciwnym razie - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania oraz bufora o domyślnym rozmiarze 1024 bajtów.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy strumień, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania oraz bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy strumień, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku strumienia, w przeciwnym razie - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania oraz bufora o określonym rozmiarze. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy strumień, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku strumienia, w przeciwnym razie - false |
| bufferSize | int | Minimalny rozmiar bufora w bajtach |

## StreamReader::StreamReader(const System::String\&) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego pliku przy użyciu kodowania UTF-8 oraz bufora o domyślnym rozmiarze 4096 bajtów.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Ścieżka do pliku, z którego odczytywane są znaki |

## StreamReader::StreamReader(const System::String\&, bool) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego pliku przy użyciu kodowania UTF-8 oraz bufora o domyślnym rozmiarze 4096 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Ścieżka do pliku, z którego odczytywane są znaki |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku pliku, w przeciwnym razie - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego pliku przy użyciu podanego kodowania oraz bufora o domyślnym rozmiarze 4096 bajtów.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Ścieżka do pliku, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego podstawowego strumienia przy użyciu podanego kodowania oraz bufora o domyślnym rozmiarze 4096 bajtów. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Ścieżka do pliku, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku pliku, w przeciwnym razie - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) konstruktor


Tworzy instancję obiektu [StreamReader](../), który odczytuje znaki z określonego pliku przy użyciu podanego kodowania oraz bufora o określonym rozmiarze. Parametr określa, czy wykrywanie znacznika kolejności bajtów ma być włączone.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Ścieżka do pliku, z którego odczytywane są znaki |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |
| detectEncodingFromByteOrderMarks | **bool** | True, aby wyszukać znaczniki kolejności bajtów na początku pliku, w przeciwnym razie - false |
| bufferSize | int | Minimalny rozmiar bufora w bajtach |

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)