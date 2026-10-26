---
title: SetLicense()
second_title: Aspose.Slides C++ API Referansı
description: Bileşeni lisanslar.
type: docs
weight: 14
url: /tr/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metot


Bileşeni lisanslar.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Tam ya da kısa bir dosya adı ya da gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |
## Açıklamalar



Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.
2. Bileşen derlemesinin klasörü.
3. İstemcinin çağıran derlemesinin klasörü.
4. Giriş derlemesinin klasörü.
5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Not:** .NET Compact Framework üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:

1. Açık yol.
2. İstemcinin çağıran derlemesindeki gömülü kaynak.

Bu örnekte, MyLicense.lic adlı bir lisans dosyasını bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemedeki gömülü kaynaklarda bulmaya çalışılacaktır. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metot


Bileşeni lisanslar.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Lisansı içeren bir akış. |
## Açıklamalar



Bu metodu bir akıştan lisans yüklemek için kullanın.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [License](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)