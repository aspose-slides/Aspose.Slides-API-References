---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova parte xml personalizzata.
type: docs
weight: 53
url: /it/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) metodo


Aggiunge una nuova parte xml personalizzata.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | La stringa xml della nuova parte da aggiungere. |

### Valore restituito

Parte xml personalizzata creata.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) metodo


Aggiunge una nuova parte xml personalizzata.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati xml della nuova parte da aggiungere. |

### Valore restituito

Parte xml personalizzata creata.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) metodo


Aggiunge una nuova parte xml personalizzata.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Il flusso di input con dati xml della nuova parte da aggiungere. |

### Valore restituito

Parte xml personalizzata creata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [String](../../../system/string/)
* Classe [CustomXmlPartCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)