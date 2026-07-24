---
title: WriteRaw()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, karakter arabelleğinden ham işaretlemeyi manuel olarak yazar.
type: docs
weight: 287
url: /tr/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metodu


Türetilmiş bir sınıfta geçersiz kılındığında, karakter arabelleğinden ham işaretlemeyi manuel olarak yazar.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Yazılacak metni içeren karakter dizisi. |
| index | **int32_t** | Yazılacak metnin başlangıcını gösteren arabelleğindeki konum. |
| count | **int32_t** | Yazılacak karakter sayısı. |

## XmlWriter::WriteRaw(const String\&) metodu


Türetilmiş bir sınıfta geçersiz kılındığında, bir dizeden ham işaretlemeyi manuel olarak yazar.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) içeren metin. |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlWriter](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)