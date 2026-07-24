---
title: SetWriteProtection()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen şifreyle bu sunum için yazma koruması ayarlayın.
type: docs
weight: 131
url: /tr/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metodu


Bu sunum için belirtilen şifreyle yazma koruması ayarlayın.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Şifre. |
## Açıklamalar



Aşağıdaki örnek kod, bir sunuma nasıl yazma koruması ayarlayacağınızı gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [ProtectionManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)