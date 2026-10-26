---
title: "System::StringExtra"
second_title: Aspose.Slides C++ için API Referansı
description: 
type: docs
weight: 911
url: /tr/system.stringextra/
---
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Dize dizisini birleştirir. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Dizeleri birleştirir. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Dizeleri birleştirir. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Dizeleri birleştirir. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Birden çok nesneyi dizeye dönüştürür ve ortaya çıkan dizeleri birleştirir. [SmartPtr](../system/smartptr/) türleri için özelleştirme. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Birden çok nesneyi dizeye dönüştürür ve ortaya çıkan dizeleri birleştirir. Aritmetik türler için özelleştirme. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Birden çok nesneyi dizeye dönüştürür ve ortaya çıkan dizeleri birleştirir. Yapılar ve diğer değer türleri için özelleştirme. |