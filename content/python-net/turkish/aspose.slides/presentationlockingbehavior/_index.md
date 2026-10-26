---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Bir [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örneğiyle çalışırken ve yüklerken [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) kaynağını (dosya veya **io.RawIOBase**) işlemeye ilişkin davranışı temsil eder.

PresentationLockingBehavior türü aşağıdaki üyeleri sunar:

## Alanlar

| Alan | Açıklama |
| :- | :- |
| LOAD_AND_RELEASE | Kaynak yalnızca [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) yapıcı çalışması süresince kilitlenir.<br/>            Eğer [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) false olarak ayarlanırsa, tüm BLOB'lar <br/>            belleğe yüklenir. Aksi takdirde, geçici dosyalar gibi başka yöntemler kullanılabilir. Bu davranış [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/tr/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)'den daha yavaştır ve kaynak sahipliğini [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)'a geçirmek mümkünse, [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/tr/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) kullanılması önerilir. |
| KEEP_LOCKED | Kaynak, [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örneğinin tüm ömrü boyunca, dispose edilene kadar kilitlenir.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) true olarak ayarlanmalıdır; aksi takdirde istisna fırlatılır. Bu davranış önerilir, [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/tr/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE)'den daha hızlıdır ve daha az bellek tüketir. |

### Notlar

Kaynak, [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) yapıcısına geçirilen parametredir. Aşağıdaki örnekte, kaynak "pres.pptx" dosyasıdır:

Bu örnek için, kaynak ("pres.pptx" dosyası) bir [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örnek ömrü boyunca kilitlenir, yani diğer işlem tarafından değiştirilemez veya silinemez.

### Diğer Bağlantılar
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)