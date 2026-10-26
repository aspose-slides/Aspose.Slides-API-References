---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides için C++ API Referansı
description: Elemanı okur ve BinHex içeriğini çözer.
type: docs
weight: 677
url: /tr/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodu

Elemanı okur ve **BinHex** içeriğini çözer.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki offset. |
| count | **int32_t** | Tampona kopyalanacak maksimum bayt sayısı. Gerçek kopyalanan bayt sayısı bu metottan döndürülür. |

### Return Value

Tampona yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlTextReader](../)
* İsim Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)