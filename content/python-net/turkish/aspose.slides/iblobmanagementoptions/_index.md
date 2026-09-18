---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions sınıf

A Binary Large Object (BLOB) tek bir varlık olarak depolanan ikili bir veridir - yani BLOB bir 
            ses, video veya sunum olabilir. BLOB'larla çalışırken bellek tüketimini optimize etmek için bir dizi teknik kullanılır - bu, zaten sunumda depolanmış ya da daha sonra programlı olarak eklenebilir. 
            [`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions) kullanarak [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örnek ömrü boyunca BLOB'ların 
            işlenmesiyle ilgili farklı davranış yönlerini değiştirebilirsiniz.

IBlobManagementOptions türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Bu özellik, Presentation sınıfının bir örneğinin ömrü boyunca kaynağın - dosyanın <br/>            veya akışın sahibi olup olamayacağını tanımlar. Eğer örnek sahibi ise, kaynağı kilitler. Bu, <br/>            BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) <br/>            Presentation'ın örnek ömrü boyunca değiştirilemez. İşte bir örnek: |
| [`is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini büyük ölçüde <br/>            azaltır ancak dosya oluşturma izinleri gerektirir.<br/>            Tüm dosyalar, sunumla çalışma tamamlandıktan sonra silinecektir. |
| [`temp_files_root_path`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak Sistem geçici dizini kullanılacaktır. <br/>            Barındırma sürecinin orada dosya ve klasör oluşturma izinlerine sahip olması gerekir. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar<br/>            belleğe yüklenir; bu limit aşıldığında yalnızca alternatif mekanizmalar (örneğin geçici<br/>            dosyalar) kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu<br/>            özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |

### Ayrıca Bakınız
* sınıf [`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)