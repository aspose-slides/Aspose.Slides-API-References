---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando viene sovrascritto in una classe derivata, atomizza la stringa specificata e la aggiunge a XmlNameTable.
type: docs
weight: 14
url: /it/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Quando viene sovrascritto in una classe derivata, atomizza la stringa specificata e la aggiunge a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | L'array di caratteri contenente il nome da aggiungere. |
| offset | **int32_t** | Indice basato su zero nell'array che specifica il primo carattere del nome. |
| length | **int32_t** | Il numero di caratteri nel nome. |

### Return Value

La nuova stringa atomizzata o quella esistente se è già presente. Se la lunghezza è zero, viene restituito [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) method


Quando viene sovrascritto in una classe derivata, atomizza la stringa specificata e la aggiunge a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Il nome da aggiungere. |

### Return Value

La nuova stringa atomizzata o quella esistente se è già presente.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)