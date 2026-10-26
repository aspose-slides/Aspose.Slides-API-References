---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, surrogate karakter çiftinin surrogate karakter varlığını oluşturur ve yazar.
type: docs
weight: 261
url: /tr/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) yöntemi

Türetilmiş bir sınıfta geçersiz kılındığında, surrogate karakter çiftinin surrogate karakter varlığını oluşturur ve yazar.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lowChar | char16_t | Düşük yedek karakter. Bu değer 0xDC00 ile 0xDFFF arasında olmalıdır. |
| highChar | char16_t | Yüksek yedek karakter. Bu değer 0xD800 ile 0xDBFF arasında olmalıdır. |

## See Also

* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)