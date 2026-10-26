---
title: StringFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de StringFormat klasse.
type: docs
weight: 1
url: /nl/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() constructor


Construeert een nieuw exemplaar van de [StringFormat](../) klasse.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) constructor


Construeert een nieuw exemplaar van de [StringFormat](../) klasse met de opgegeven formatvlaggen en taal.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Een bitwise combinatie van StringFormatFlags enumwaarde die het tekenreeksformaat specificeert dat door het te creëren object wordt weergegeven |
| language | **int32_t** | Een taal van de tekst |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) constructor


Copyconstructor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Een [StringFormat](../) object om van te kopiëren |

## Zie ook

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringFormat](../)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)