---
title: ColorTranslator
second_title: Aspose.Slides for C++ API Referansı
description: "Renk çevirileri gerçekleştirir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) veya operator new ile oluşturmayın; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 66
url: /tr/system.drawing/colortranslator/
---
## ColorTranslator sınıfı

Renk çevirileri gerçekleştirir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new kullanarak oluşturmayın; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ColorTranslator
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Belirtilen HTML renk temsilini eşdeğer [Color](../color/) nesnesine dönüştürür. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Belirtilen [Windows](../../system.windows/) rengi eşdeğer [Color](../color/) nesnesine dönüştürür. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Belirtilen [Color](../color/) nesnesini eşdeğer HTML rengin string temsiline dönüştürür. |

## Diğer Bölümler

* Ad Alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)