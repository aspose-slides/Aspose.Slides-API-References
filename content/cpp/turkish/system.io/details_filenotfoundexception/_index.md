---
title: Details_FileNotFoundException
second_title: Aspose.Slides için C++ API Referansı
description: "Diskte mevcut olmayan bir dosyaya erişim girişimi başarısız olduğunda fırlatılan istisna. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine FileNotFoundException sınıfını kullanın. FileNotFoundException sınıfı örneklerini System::SmartPtr içine asla sarmalamayın."
type: docs
weight: 183
url: /tr/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException sınıf


Diskte bulunmayan bir dosyaya erişim girişimi başarısız olduğunda fırlatılan istisna. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine FileNotFoundException sınıfını kullanın. FileNotFoundException sınıfı örneklerini [System::SmartPtr](../../system/smartptr/) içine asla sarmalayın.

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Bu istisnaya neden olan dosyanın adını döndürür. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## Ayrıca Bakınız

* Sınıf [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* İsim alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)