---
title: LoadingStreamBehavior
second_title: Aspose.Slides C++ API Referansı
description: "Bir metoda geçirilen System::IO::Stream, Binary Large Object (BLOB) olarak kabul edilir (IBlobManagementOptions açıklamasına bakınız). Bu enumun değerleri, System::IO::Stream’in metoda geçirildiğinde nasıl ele alınacağını belirler. Gereksinimlere bağlı olarak, en verimli davranışı sağlamak için farklı kararlar alınabilir."
type: docs
weight: 6735
url: /tr/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

[System::IO::Stream](../../system.io/stream/) bir metoda parametre olarak verildiğinde Binary Large Object (BLOB) olarak kabul edilir ([IBlobManagementOptions](../iblobmanagementoptions/) açıklamasına bakınız). Bu enum değerleri, [System::IO::Stream](../../system.io/stream/) metod'a geçirildiğinde nasıl ele alınacağını belirler. Gereksinimlere bağlı olarak, en verimli davranışı sağlamak için farklı kararlar alınabilir.

```cpp
enum class LoadingStreamBehavior
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Akış sona kadar okunacak ve ardından serbest bırakılacak - yani bu akışın gelecekte [IPresentation](../ipresentation/) örneği tarafından kullanılmayacağı garanti edilir. İstemci kodu tarafından kapatılabilir veya başka herhangi bir şekilde kullanılabilir. |
| KeepLocked | 1 | Akış [IPresentation](../ipresentation/) nesnesi içinde kilitlenecek, yani akışın sahipliği devredilecek. [IPresentation](../ipresentation/) nesnesi, bu nesne kendisi imha edildiğinde akışı doğru şekilde temizlemekten sorumlu olacaktır. Bu davranış, büyük bir BLOB dosyasını (örneğin büyük bir video veya ses - [IBlobManagementOptions](../iblobmanagementoptions/) açıklamasına bakınız) serileştirmeniz ve bu dosyanın belleğe yüklenmesini ya da diğer performans sorunlarını önlemeniz gerektiğinde son derece faydalıdır. Bu dosya için sadece [System::IO::FileStream](../../system.io/filestream/) açabilir ve bir metoda geçirirken [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior seçebilirsiniz. |

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)