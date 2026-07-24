---
title: ToArray()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm yorumları içeren bir dizi oluşturur ve döndürür.
type: docs
weight: 105
url: /tr/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metodu


Tüm yorumları içeren bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Dönüş Değeri

[Comment](../../comment/) dizisi.

## CommentCollection::ToArray(int32_t, int32_t) metodu


Belirtilen aralıktaki tüm yorumları içeren bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Döndürülecek ilk yorumun indeksi. |
| count | **int32_t** | Döndürülecek yorum sayısı. |

### Dönüş Değeri

[Comment](../../comment/) dizisi.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComment](../../icomment/)
* Sınıf [CommentCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)