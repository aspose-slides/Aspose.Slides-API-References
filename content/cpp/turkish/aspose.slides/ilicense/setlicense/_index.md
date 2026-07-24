---
title: SetLicense()
second_title: Aspose.Slides için C++ API Referansı
description: Bileşeni lisanslar.
type: docs
weight: 1
url: /tr/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metot

Bileşeni lisanslar.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Tam veya kısa bir dosya adı ya da gömülü bir kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

## Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Belirtilen yol.
2. Bileşen derlemesinin klasörü.
3. İstemcinin çağıran derlemesinin klasörü.
4. Giriş derlemesinin klasörü.
5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Not:** .NET Compact Framework üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:

1. Belirtilen yol.
2. İstemcinin çağıran derlemesindeki gömülü kaynak.

Bu örnekte, bileşeni içeren klasörde, çağıran derlemenin bulunduğu klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulmaya çalışılacaktır.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metot

Bileşeni lisanslar.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Lisansı içeren bir akış. |

## Açıklamalar

Bu yöntemi bir akıştan lisans yüklemek için kullanın.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ILicense](../)
* Sınıf [Stream](../../../system.io/stream/)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)