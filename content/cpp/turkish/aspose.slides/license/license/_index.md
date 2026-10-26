---
title: License()
second_title: Aspose.Slides for C++ API Referansı
description: Bu sınıfın yeni bir örneğini başlatır.
type: docs
weight: 1
url: /tr/aspose.slides/license/license/
---
## License::License() yapıcı

Bu sınıfın yeni bir örneğini başlatır.

```cpp
Aspose::Slides::License::License()
```

## Açıklamalar

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesini içeren klasörde ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## İlgili

* Sınıf [License](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)