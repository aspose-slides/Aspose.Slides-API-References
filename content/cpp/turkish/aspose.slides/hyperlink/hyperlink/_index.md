---
title: Hyperlink()
second_title: Aspose.Slides for C++ API Referansı
description: Bir hyperlink örneği oluşturur.
type: docs
weight: 339
url: /tr/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) yapıcı

Bir hyperlink örneği oluşturur.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) yapıcı

Belirli bir slayta işaret eden bir hyperlink örneği oluşturur. Not: oluşturulan hyperlink aynı sunumdan bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Hedef slayt. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) yapıcı

Başka bir hyperlink'i kaynak olarak kullanarak, ikincil özellikleri geçersiz kılarak bir hyperlink örneği oluşturur.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Kaynak hyperlink |
| targetFrame | [System::String](../../../system/string/) | Hedef çerçeve |
| tooltip | [System::String](../../../system/string/) | Araç ipucu metni |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Hyperlink](../)
* Sınıf [ISlide](../../islide/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)