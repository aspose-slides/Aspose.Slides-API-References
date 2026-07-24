---
title: CreatePortion()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir metin bölümü oluşturur.
type: docs
weight: 1
url: /tr/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() yöntemi

Boş bir metin bölümünü oluşturur.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Dönüş Değeri

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) yöntemi

Belirtilen dizeden bir metin bölümü oluşturur.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Dize. |

### Dönüş Değeri

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) yöntemi

Belirtilen bölüm verisini kullanarak bir bölüm oluşturur.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Kullanılacak bir bölüm. |

### Dönüş Değeri

[Portion](../../portion/).

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPortion](../../iportion/)
* Sınıf [PortionFactory](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)