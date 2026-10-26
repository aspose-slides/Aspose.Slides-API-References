---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Bir metoda geçirilen **io.RawIOBase**, Binary Large Object (BLOB) olarak kabul edilir (bkz. [`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions) açıklaması). Bu enumun değerleri, **io.RawIOBase**'in metoda geçirilirken nasıl işleneceğini belirler. Gereksinimlere bağlı olarak, en verimli davranışı sağlamak için farklı kararlar verilebilir.

LoadingStreamBehavior türü aşağıdaki üyeleri sunar:

## Alanlar

| Alan | Açıklama |
| :- | :- |
| READ_STREAM_AND_RELEASE | Akış, sonuna kadar okunacak ve ardından serbest bırakılacak - yani bu akışın gelecekte [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örneği tarafından kullanılmayacağı garantilenir. <br/>            İstemci kodu tarafından kapatılabilir veya başka bir şekilde kullanılabilir. |
| KEEP_LOCKED | Akış, [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) nesnesi içinde kilitlenecek, yani sahipliği <br/>            akış aktarılacak. [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) nesnesi sorumlu olacaktır <br/>            bu nesne kendisi yok edildiğinde akışı düzgün şekilde dispose etmek için. <br/>            Bu davranış, büyük bir BLOB dosyasını (örneğin büyük bir <br/>            video veya ses -[`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions) açıklamasına bakınız) ve bu dosyanın yüklenmesini <br/>            belleğe almasını veya diğer performans sorunlarını önlemek istediğinizde son derece kullanışlıdır. **System.IO.FileStream** <br/>            bu dosya için açabilir ve bir metoda geçerek [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/tr/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior seçebilirsiniz. |

### Ayrıca Bakınız
* sınıf [`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)