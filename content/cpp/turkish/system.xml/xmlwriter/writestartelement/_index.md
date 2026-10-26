---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen ad alanı ile ilişkilendirir.
type: docs
weight: 92
url: /tr/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen ad alanı ile ilişkilendirir.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Öğenin yerel adı. |
| ns | const [String](../../../system/string/)\& | Öğeye ilişkilendirilecek ad alanı URI'si. Bu ad alanı zaten kapsam dahilindeyse ve ilişkilendirilmiş bir ön ek varsa, yazar otomatik olarak bu ön eki de yazar. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen ad alanı ve ön ek ile ilişkilendirir.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Öğenin ad alanı ön eki. |
| localName | const [String](../../../system/string/)\& | Öğenin yerel adı. |
| ns | const [String](../../../system/string/)\& | Öğeye ilişkilendirilecek ad alanı URI'si. |

## XmlWriter::WriteStartElement(const String\&) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad ile bir başlangıç etiketi yazar.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Öğenin yerel adı. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlWriter](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)