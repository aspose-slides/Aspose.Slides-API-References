---
title: StreamReader()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un'istanza dell'oggetto StreamReader che legge caratteri dallo stream sottostante specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte.
type: docs
weight: 1
url: /it/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante da cui leggere i caratteri |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante da cui leggere i caratteri |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio dello stream, altrimenti - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica specificata e un buffer con dimensione predefinita di 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica specificata e un buffer con dimensione predefinita di 1024 byte. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio dello stream, altrimenti - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica specificata e un buffer della dimensione specificata. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio dello stream, altrimenti - false |
| bufferSize | int | La dimensione minima del buffer in byte |

## StreamReader::StreamReader(const System::String\&) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dal file specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Il percorso del file da cui leggere i caratteri |

## StreamReader::StreamReader(const System::String\&, bool) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dal file specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 4096 byte. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Il percorso del file da cui leggere i caratteri |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio del file, altrimenti - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dal file specificato usando la codifica specificata e un buffer con dimensione predefinita di 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Il percorso del file da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dallo stream sottostante specificato usando la codifica specificata e un buffer con dimensione predefinita di 4096 byte. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Il percorso del file da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio del file, altrimenti - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) costruttore


Crea un'istanza dell'oggetto [StreamReader](../) che legge caratteri dal file specificato usando la codifica specificata e un buffer della dimensione specificata. Un parametro specifica se il rilevamento del marcatore di ordine dei byte deve essere abilitato.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Il percorso del file da cui leggere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da usare |
| detectEncodingFromByteOrderMarks | **bool** | True per cercare i marcatori di ordine dei byte all'inizio del file, altrimenti - false |
| bufferSize | int | La dimensione minima del buffer in byte |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [Stream](../../stream/)
* Classe [StreamReader](../)
* Classe [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)