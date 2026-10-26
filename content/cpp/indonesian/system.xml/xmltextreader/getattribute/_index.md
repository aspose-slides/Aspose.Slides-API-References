---
title: GetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai atribut dengan nama yang ditentukan.
type: docs
weight: 495
url: /id/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metode


Mengembalikan nilai atribut dengan nama yang ditentukan.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang memenuhi syarat dari atribut. |

### Return Value

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan.

## XmlTextReader::GetAttribute(String, String) metode


Mengembalikan nilai atribut dengan nama lokal dan URI namespace yang ditentukan.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari atribut. |

### Return Value

Nilai atribut yang ditentukan. Jika atribut tidak ditemukan, **nullptr** dikembalikan. Metode ini tidak memindahkan pembaca.

## XmlTextReader::GetAttribute(int32_t) metode


Mengembalikan nilai atribut dengan indeks yang ditentukan.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. Indeks dimulai dari nol. (Atribut pertama memiliki indeks 0.) |

### Return Value

Nilai atribut yang ditentukan.

## See Also

* Kelas [String](../../../system/string/)
* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)